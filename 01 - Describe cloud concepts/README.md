# 01 - Describe Cloud Concepts

## Describe Cloud Computing

> **Cloud computing** is the delivery of computing services over the internet.

- The shared responsibility model means that the responsibility of maintaining a data center gets passed on to the cloud provider.

### Cloud Models

- **Private Cloud**

  - Cloud used by a single entity
  - Data is only yours
  - Mostly hosted in a datacenter of your company
  - Greater costs, more responsibility but more security

- **Public Cloud**

  - Build and controlled by a third-party cloud provider
  - Anyone can access and use resources
  - No CapEx to scale up
  - Pay for what you use
  - Not complete control over resources and security

- **Hybrid Cloud**

  - Public + Private cloud
  - Private cloud can provision resources on the public cloud in cases of emergency
  - Users can choose which services to keep in the public cloud and which ones to keep in the private cloud

- **Multi-cloud**

  - Multiple cloud providers
  - Manage resources and security in both environments

- **Azure Arc**

  - Set of technologies that helps manage your cloud environment.
  - Works for all cloud configurations

- **Azure VMware Solution**

  - Run VMware workloads in Azure with seamless integration and scalability.
  - Ideal for migrating VMs from private cloud to Azure.

### CapEx v/s Opex

- CapEx is one-time fee to buy tangible resources. It stands for Capital Expenses.
- OpEx is spending money on products over time to keep things operational. Hence its called operational expenses. Cloud computing falls under OpEx.

> Cloud computing follows the _pay-as-you-go_ model.

---

## Describe the benefits of using cloud services

### High Availability

- SLA (service level agreement) defines the uptime of a service through a formal agreement between the service provider and the customer.
- This is a percentage which tells you the uptime of a service. Could also define the downtime. It also tells you what compensation will be provided if the SLA is not met. 4 nines is `99.99%` uptime. There is huge difference between `99%` and `99.9%`.

## Scalability

- Ability to adjust resources to meet demand.
- This also prevents you from overpaying for services
- Vertical scaling is focused on increasing or decreasing the capabilities of resources. Horizontal scaling is adding or subtracting the number of resources.

### Reliability

- Ability to recover from failures and continue to function
- Decentralized
- You can setup the app to do this or this automatically happens at times

### Predictability

- Can predict performance and costs
- For ex -> If you suddenly need more resources, autoscaling can deploy additional resources to meet the demand, and then scale back when the demand drops.
- You can even use tools like the Total Cost of Ownership (TCO) or Pricing Calculator to get an estimate of potential cloud spend.

### Security and governance in the cloud

- Cloud features support governance, compliance, and security by ensuring resources meet corporate and regulatory standards through set templates, cloud-based auditing, and automatic updates or patches.
- Different cloud models offer varying control over security, with Infrastructure as a Service (IaaS) providing maximum control, while Platform as a Service (PaaS) and Software as a Service (SaaS) handle maintenance and patches automatically, enhancing both security and governance.

### Managageability in the cloud

- **Management of the cloud**

  Manage Cloud Resources once they are out there

  - Scale resources based on need
  - Deploy resources
  - Monitoring and Alerting

- **Management in the cloud**

  How you manage the cloud resources that are out there

  - Web Portal
  - CLI
  - APIs

## Cloud Service Types

### Infrastructure as a service (IaaS)

- Most flexible
- Maximum control
- Harware, internet connection and physical security is handled by the cloud provider
- The user is responsible for everything else.
- This is essentially just renting hardware.

### Platform as a Service (PaaS)

- Middleground between `IaaS` and `SaaS`
- In this, the cloud provider also maintains the OS, middleware, dev tools and business servoces. You don't worry about licensing or patching.
- It is a complete development environment.
- Cloud provider may be responsible for networking settings and connectivity within your cloud environment, network and application security, and the directory infrastructur.

### Software as a Service (SaaS)

- SaaS basically a fully-developed application
- Least flexible but most easy to get up and running
- You are only responsible for the data that you put in the system
