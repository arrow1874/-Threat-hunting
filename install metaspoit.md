To trigger image analysis for an image in a registry, push the image to a registry that's integrated with Docker Scout, to a repository where image analysis is activated.
sudo apt autoremove
 <img width="1889" height="949" alt="do v 1" src="https://github.com/user-attachments/assets/b5a084a0-5e24-4c95-9907-ab7576c00ef6" />
Team scan all the devops enviroment  docker build --push --tag <org>/<image:tag> --provenance=true --sbom=true 
SOC team scan with docker scout to see the target applications images vaulnerability 
CVE reports
The docker scout cves command gives you a complete view of all the vulnerabilities in the image. This command supports several flags that lets you specify more precisely which vulnerabilities you're interested in, for example, by severity or package type:
SOC and hunt team afer scanning and analysing the report to follow up with the Vulnerability team for the early discovered critical isuess to be patched and other needed images upgrade ASAp. Playbook should be created for team continued work process.<img width="1889" height="988" alt="do v 12" src="https://github.com/user-attachments/assets/20063d40-b5ca-4c2f-996f-42701b345c43" />
