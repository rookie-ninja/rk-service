# rk-service
Contains Entry which is service wide like OAuth, ExchangeRate and etc

## Why we need it?
We hope to make life of developers much more easier by inject non-core functionality miscro services into your system instead of implementing it!

Non-core functionality is not the core value of your system, however, it is menditary to make a high quality product. As a result, we may spend over 30% of our workloads by dealing with it!

For example, we hope to implement a cloud photo gallary SaaS. 
The core functionality for the SaaS is Store/Read/List/Delete photos, UI design, Image processing and etc. 
The non-core functionality is Login, Security, Monitoring, Cost reduction and etc.

What we hope is provide a **Executable, Plugable** Entry to users to reduce the workloads of implementing non-core functionalities.
All user has to do is pull & run services which can be configrable vi YAML config. User can access these services via well defined API.

All the services in this package will be designed based on [rk-boot](https://github.com/rookie-ninja/rk-boot).

## Hope this will work!
