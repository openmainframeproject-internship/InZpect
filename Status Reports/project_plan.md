**Student's Name:** Sudhanshu Joshi

**Mentor:** Joe Devlin

**Project:** InZpect

**Project Description:** InZpect is next generation dump viewer and inspector that is something of a successor to IPCS. There is a lot of work to do in UI and testing. Plus almost any work on the internals requires lots of knowledge of the operating system. SVCDumps are not highly structured, so the relationships of data and state of the computation must be synthesized from the memory blocks in the dump, primarily. The server is written in java, with some back-end code coming from extensions/usage of the ZSS in Zowe. The client code is in Javascript using React. The tooling is very minimal currently, as is the number of third-party libraries.

**Problem Definition:** Use of debugger extensions in various code editors helps a developer a lot. In this project we will be working to build a debugger and debugger extension for remotely debugging the Z assembler code. This will involve working through LSP and DAP.

**Deliverables:** 
* Implement a debugger extension for Z assembler on VS code and Eclipse theia

**Coding Plan**

| Week | Tasks | Goals |
| ---- | ---- | --- |
| 1 | Explore LSP and DAP | Understand the working of extensions and debuggers |
| 2 | Explore working of clangd | Since our project will work in a similar way hence to get an idea of it |
| 3 | Environment Setup | Having access to ZOS(mainframe) instance and set things locally |
| 4 | Try out building a sample Language server and debugger | Understanding how code communicates with different layer | 
| 5 | Discuss the architecture for the project | Plan the implementation on a broader level | 
| 6 | Discuss a MVP | Plan more precisely and make various design decisions | 
| 7 |  Start working on MVP | To get started working with the real debugger code | 
| 8 | Work on MVP and try/test it out | To get an idea of how the integration is working | 
| 9 | Complete the MVP, have a discussion on it with mentor | Review the design decisions |
| 10 | Discuss a larger plan and all the features | Dig deeper into the implemenation and decide various debugging features to be implemented and how |
| 11 | Add more debugger features | adding more functionality in the extension | 
| 12 | Implement more features and try them out | Test with proper integration |
| 13 | Write tests | Cover all areas of bug | 
| 14 | Fix the bugs and refactor code | V1 release | 
| 15 | Improve more on the debugger extension and check for performance | check for time efficiency of communication between debugger and editor | 
| 16 | Implement the same for Eclipse Theia | Providing the same for eclipse theia editor | 
| 17 | Implement for Zowe editor | Providing the same for Zowe editor | 
| 18 | Write proper documentation and refactor code | Documentation for Architecture | 
| 19 | Write proper documentation for onboarding | Documentation for usage and contribution | 
| 20 | Work on demo and video | Publish the demo and video | 
