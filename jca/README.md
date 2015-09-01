==============
JCA Examples
==============
This project provides encryption/decryption prototypes using the JCA APIs.

**Requirements**
- JDK 1.7 or JDK 1.8
- JCE Unlimited Strength Jurisdiction Policy Files for JDK/JRE 7 or JDK/JRE 8

**How to install JCE extention files for JDK/JRE 7**  
1. Go to the Oracle Java download page http://www.oracle.com/technetwork/java/javase/downloads/jce-7-download-432124.html 
2. Accept license agreement and download the UnlimitedJCEPolicyJDK7.zip  
3. Unzip the downloaded zip  
4. Copy local_policy.jar and US_export_policy.jar to the $JAVA_HOME/jre/lib/security (Note: these jars will be already there so you have to overwrite them)  

**How to install JCE extention files for JDK/JRE 8**  
1. Go to the Oracle Java download page http://www.oracle.com/technetwork/java/javase/downloads/jce8-download-2133166.html
2. Accept license agreement and download the jce_policy-8.zip  
3. Unzip the downloaded zip  
4. Copy local_policy.jar and US_export_policy.jar to the $JAVA_HOME/jre/lib/security (Note: these jars will be already there so you have to overwrite them)  


**Checking out from github**
```  
###GIT  
> git clone https://github.com/datavirtualization/java-crypto.git

```
**Run Maven build**  
```
> cd java-crypto/jca
> mvn install
```