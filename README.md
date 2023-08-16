# V1-CS-Ambassadors Challenge Excercise
---
Lets Deploy an ECS Cluster.

![Diagram](/images/ecs-diag.jpg)

### 1. Launch this CFT template to deploy an ECS cluster with Fargate as the compute type.

[![Launch Stack](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=v1es-ecs-fargate&templateURL=https://immersionday-workshops-trendmicro.s3.amazonaws.com/container-security/v1cs-ecs.yaml)

**Before Continuing Make sure Stack completes successfully**
![Diagram](/images/cft.jpg)

---
### 2. Deploy the Vision One Connector.
- **Service Management > Cloud Accounts > +Add Account**
- Make sure to toggle ON support for ECS containers.
- Accept the default provided parameters and launch the stack.

![connection](/images/v1es-1.jpg)

### 3. Once the stack completes.
- Click Outputs on the completed Stack.
- Copy the IAM role ARN value.
- Paste the ARN back in Cloud One, give the Account an identifier name.
- Save

![connection](/images/v1cs-2.jpg)
![connection](/images/v1cs-3.jpg)

---

## Awesome Connection has been established lets check for any introduced Risks into my environment.
- In Vision One: Cloud Security Operations > Container Security > Container Protection
- Select the **Vulnerability** tab
- Select **ECS** tab.

![connection](/images/v1cs-view.jpg)

---
