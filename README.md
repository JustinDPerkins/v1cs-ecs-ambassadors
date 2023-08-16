# V1-CS-Ambassadors Challenge Excercise
---
Lets Deploy an ECS Cluster.
![Integration](/images/root.png)

### 1. Launch this CFT template to deploy an ECS cluster with Fargate as the compute type.

[![Launch Stack](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=v1es-ecs-fargate&templateURL=https://immersionday-workshops-trendmicro.s3.amazonaws.com/application-security/c1as-fargate-workshop.yaml)

---
### 1. Deploy the Vision One Connector.
- **Service Management > Cloud Accounts > +Add Account**
- Make sure to toggle ON support for ECS containers.
- Accept the default provided parameters and launch the stack.
- Image1 goes here ![Integration](/images/root.png)

### 2. Once the stack completes.
- Click Outputs on the completed Stack.
- Copy the IAM role ARN value.
- Paste the ARN back in Cloud One, give the Account an identifier name.
- Save
-Image2 goes here ![Integration](/images/root.png)
-Image3 ![Integration](/images/root.png)

---

## Awesome Connection has been established lets check for any introduced Risks into my environment.

---
