# DroidWare

DroidWare is a synthetic dataset designed to address the problem of malware detection in Android-based environments. The dataset is composed of 278 normal (non-malware) and 121 positive (malware) samples, which were obtained by analysing network traffic data. Malware samples were obtained and analyzed by VirusTotal 1 (https://www.virustotal.com), which is an on-line scanning tool for malware detection. The positive samples were collected from several random manifests and different applications at Google Play Store (https://play.google.com/). 

Since each dataset sample stands for a different application, we used the permissions of that application to access Android resources and device actions as the features. Therefore, each dataset sample is composed of 152 features (permissions). Please, consider taking look at “LIST_PERMISSIONS.pdf” file for a deeper explanation about that specific permissions.

