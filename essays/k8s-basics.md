# K8s 

<p>
  <img src="/root/the-sailors/handbook/assets/DALL·E 2023-05-03 22.59.51.png" alt="image_alt_text">
</p>

## Topics

* Initial Setup
    * Keep everything as IAC it will be good for your memory
    * Daily backups will let your cluster more safe for unexpected accidents
* Please make sure to give our applications the attention they deserve. Configuration of simple alerts, like:
    * CPU/Memory and Volume
    * CrashLoopBack
    * Pod Disruption Budget
* Give our application deployed into k8s, the power to access the cloud stack and secrets without the necessity to shared keys/secrets:
    * Secret Manager/Container Registry & Cloud Stack

* Maybe have a unified way to Continuos integration/deployment can be useful for entire company. 

* Separe the infraestrure configs from the true codebase