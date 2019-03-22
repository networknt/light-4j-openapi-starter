# light-4j-starter

[Stack Overflow](https://stackoverflow.com/questions/tagged/light-4j) |
[Google Group](https://groups.google.com/forum/#!forum/light-4j) |
[Gitter Chat](https://gitter.im/networknt/light-4j) |
[Subreddit](https://www.reddit.com/r/lightapi/) |
[Youtube Channel](https://www.youtube.com/channel/UCHCRMWJVXw8iB7zKxF55Byw) |
[Documentation](https://doc.networknt.com) |
[Contribution Guide](https://doc.networknt.com/contribute/) |

Light-4j is aiming at microservices in the cloud, and we care about the final deliverable size whether an application is packaged into a jar or a container image. That is why we have a lot of modules in the light-4j and other repositories so that users can pick up the right modules they use in their application. It gives flexibility for advanced users but sometimes confuses the beginners as they have to figure out which modules need to be included in the application pom.xml dependencies. The light-codegen can mitigate the burdens, but not everyone is using it. To help users who are building services from scratch, we are going to provide starter pom.xml projects in this repository and push them to the maven central. Users can include one or more starters for the application dependencies to get all typical dependencies per framework. For advanced users, they can exclude some of the modules they are not using to customize the dependencies. 

