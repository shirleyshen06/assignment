# assignment

•  What is maven role? what it be used to do?

  project management tool ,used for projects build, dependency and documentation. 




•  What is the lifecycle of maven? could you tell me the details?


   1.Validate,  validate the project is correct and all necessary information is available

   2.Compile, compile the source code of the project

   3.Test,  test the compiled source code using a suitable unit testing framework. These tests should not require the code be packaged or deployed

   4.Package, take the compiled code and package it in its distributable format, such as a JAR.

   5.Integration test,Performs the test for maintaining integration.   
   6.Verify,run any checks on results of integration tests to ensure quality criteria are met

   7.Install ,install the package into the local repository, for use as a dependency in other projects locally

   8. Deploy,done in the build environment, copies the final package to the remote repository for sharing with other developers and projects.




•  what is the difference between package and install in maven lifecycle?

package will compile your code and also package it. For example, if your pom says the project is a jar, it will create a jar for you when you package it and put it somewhere in the target directory (by default). install will compile and package, but it will also put the package in your local repository.



•  What is difference between passing by value and passing by reference? Could you design a code to verify your understanding and screenshot it to me?
   
   Java lang is always passed by value, which the value could be either the copy of bit address of the Heap objects held by an object-handler 
   called reference (which always resides on the left side of "=" expression), or the actaul value of the primitive types passed(copied) to
   the variable.



