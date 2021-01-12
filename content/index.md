## What does it do?

Information security monitoring is complex, and setting up an environment to learn or test complicated things using complex systems can be a big time sink, or even a complete blocker. Whether you're a novice learner, junior red-teamer, or a veteran operator, Thremulation Station aims to provides a smooth path to executing threats and observing them using [Elastic Security](https://www.elastic.co/guide/en/security/current/es-overview.html) all within the same platform. And what if I told you it could all be done from your laptop??

![](images/ts-workflow.png)



## What are the requirements?

Our goal from the beginning has been to provide a small and useful range that can operate on a laptop with a minimum of ***4 threads available*** and ***8G of RAM***. Obviously the more the better, but the minimum specs with get the job done.  


## How does it work?

The project is a collection of existing virtualization tools like VirtualBox and Vagrant an to deploy a local testing environment that requires only a _reasonably_ spec'd machine. Once the environment is built, users can start simulating and detecting traffic primarily using [Elastic Security](https://www.elastic.co/guide/en/security/current/es-overview.html) and [Atomic Redteam](https://github.com/redcanaryco/atomic-red-team).


## Who was it built for?

This project has many practical use cases, and we're excited to see how the community uses TS. Here are a few examples that we had in mind while creating the project.

- Cyber defense education
- Generating training data
- Threat intelligence training
- Writing and validating [detection rules](https://github.com/elastic/detection-rules)
- Writing and testing threat [tactics and techniques](https://attack.mitre.org/tactics/enterprise/)