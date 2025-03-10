---
languages:
- vb
 products:
- dotnet-core
- windows
page_type: sample
name: "MEF Sample: Simple Calculator"
urlFragment: "simple-calculator-vb"
description: "A .NET Core console application that contains the example method from Simple Calculator MEF Application in Visual Basic."
---

# Introduction

The simplest way to see what Managed Extensibility Framework can do is to build a simple MEF application. In this example, you build a very simple calculator named SimpleCalculator. The goal of SimpleCalculator is to create a console application that accepts basic arithmetic commands, in the form "5+3" or "6-2", and returns the correct answers. Using MEF, you will be able to add new operators without changing the application code.

NOTE: The purpose of SimpleCalculator is to demonstrate the concepts and syntax of MEF, rather than to necessarily provide a realistic scenario for its use. Many of the applications that would benefit most from the power of MEF are more complex than SimpleCalculator. For more extensive examples, see [Managed Extensibility Framework](https://github.com/MicrosoftArchive/mef) samples.

## Building the Sample

To download and run the sample, follow these steps:

 1. Download and unzip the sample.
    
 2. In Visual Studio (2019 or later):
 
    1. On the menu bar, choose File, Open, Project/Solution.
 
    2. Navigate to the folder that holds the unzipped sample code, and open the solution (.sln) file.
 
    3. Choose the F5 key, or Ctrl+F5 keys, to run the project.

3. From the command line:

   1. Navigate to the folder that holds the unzipped sample code.
   
   2. At the command line, type `dotnet run`.
      
 ## More Information
 
  - https://docs.microsoft.com/en-us/dotnet/framework/mef/
