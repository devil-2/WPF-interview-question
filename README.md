# WPF Interview Questions & Answers

> Click :star:if you like the project. Pull Request are highly appreciated. Follow me [@kansiris87](https://twitter.com/kansiris87) for technical updates.

### Table of Contents

| No. | Questions |
|---- | ---------
|1    | [What is WPF?](#What is WPF?)|
|2 | [What are the types of documents supported by WPF?](#What are the types of documents supported by WPF?)|
|3 | [Is it right to say that WPF has replaced DirectX?](#Is it right to say that WPF has replaced DirectX?)|
|4 | [What are Freezable objects in WPF?	](#What are Freezable objects in WPF?	)|
|5 | [How can the size of StatusBar be increased proportionally?](#How can the size of StatusBar be increased proportionally?)|
|6 | [What are dependency properties?	](#What are dependency properties?	)|
|7 | [Why should WPF be preferred over Adobe Flash?](#Why should WPF be preferred over Adobe Flash?)|
|8 | [How is Silverlight different from WPF browser application?](#How is Silverlight different from WPF browser application?)|
|9 | [Write about PRISM?](#Write about PRISM?)|
|10| [Is it possible to use Windows Forms in a WPF application?](#Is it possible to use Windows Forms in a WPF application?)|
|1    | [Describe CustomControl briefly?](#Describe CustomControl briefly?)|
|2 | [Name the common assemblies used in WPF?](#Name the common assemblies used in WPF?)|
|3 | [Define Path animations in WPF?](#Define Path animations in WPF?)|
|4 | [Can WPF applications be made without XAML?	](#Can WPF applications be made without XAML?)|
|5 | [What are the types of windows in WPF?](#What are the types of windows in WPF?)|
|6 | [How can elements in a ListBox be sorted?](#How can elements in a ListBox be sorted?	|
|7 | [Explain Routed events in WPF?](#Explain Routed events in WPF?)|
|8 | [How is MVVM different from MVC?](#How is MVVM different from MVC?)|
|9 | [How is System.Windows.Media.Visual dll utilized in WPF?](#How is System.Windows.Media.Visual dll utilized in WPF?)|
|10| [What are the various layout panels in WPF?](#What are the various layout panels in WPF?)|
|1    | [What does BAML mean in WPF?](#What does BAML mean in WPF?)|
|2 | [What is Difference between Page and Window Controls in WPF?](#What is Difference between Page and Window Controls in WPF?)|
|3 | [What are Attached Properties in WPF?](#What are Attached Properties in WPF?)|
|4 | [What is the INotifyPropertyChanged Interface?](#What is the INotifyPropertyChanged Interface?)|
|5 | [What is the basic difference between Events and Commands in the MVVM Model?](#What is the basic difference between Events and Commands in the MVVM Model?)|
|6 | [What is the method to force close a ToolTip, which is currently visible?](#What is the method to force close a ToolTip, which is currently visible?)	|
|7 | [ Write the differences between DynamicResource and StaticResource?](#Write the differences between DynamicResource and StaticResource?)|
|8 | [ Explain MVVM pattern?](# Explain MVVM pattern?)|
|9 | [Why are layout panels needed for in WPF?](#Why are layout panels needed for in WPF?)|
|10| [Write about UserControl in brief?](#Write about UserControl in brief?)|
|1    | [What is the way to determine if a Freezable object is Frozen?](#What is the way to determine if a Freezable object is Frozen?)|
|2 | [What is the unit of measurement in WPF?](#What is the unit of measurement in WPF?)|
|3 | [What is an adorner?](#What is an adorner?)|
|4 | [Explain Serialization?](#Explain Serialization?)|
|5 | [Is MDI supported in WPF?](#Is MDI supported in WPF?)|
|6 | [What is XBAP?](#What is XBAP?)	|
|7 | [In what sense are WPF and Silverlight similar?](#In what sense are WPF and Silverlight similar?)|
|8 | [How to make a ToolTip appear while hovering over a disabled element?](#How to make a ToolTip appear while hovering over a disabled element?)|
|9 | [How can ListBox be made to scroll smoothly?](#How can ListBox be made to scroll smoothly?)|
|10| [Where does the execution start in a WPF application?](#Where does the execution start in a WPF application?)|
|1    | [Can Windows Service be created Using WPF?](#Can Windows Service be created Using WPF?)|
|2 | [What are the different kinds of Routed events in WPF?](#What are the different kinds of Routed events in WPF?)|
|3 | [Why is it better to wrap items in ComboBoxItem?](#Why is it better to wrap items in ComboBoxItem?)|
|4 | [How to get Automation IDs of items in a ItemsControl?](#How to get Automation IDs of items in a ItemsControl?)|
|5 | [Which NameSpace has ‘Popup’ and ‘Thumb’ controls?](#Which NameSpace has ‘Popup’ and ‘Thumb’ controls?)|
|6 | [How can command-line arguments be retrieved in a WPF application?](#How can command-line arguments be retrieved in a WPF application?)	|
|7 | [What is Windows Workflow Foundation (WF)?](#What is Windows Workflow Foundation (WF)?)|
|8 | [What are the components of WF 4.0?](#What are the components of WF 4.0?)|
|9 | [What is the advantage of using WF?](#What is the advantage of using WF?)|
|10| [What is Sequential workflow?](#What is Sequential workflow?)|
|1    | [What is State Machine workflow?](#What is State Machine workflow?)|
|2 | [What is Rules-driven Workflow?](#What is Rules-driven Workflow?)|
|3 | [How can we define and edit a workflow?](#How can we define and edit a workflow?)|
|4 | [How does WF allows the workflow to update the Host Application?](#How does WF allows the workflow to update the Host Application?)|
|5 | [What is a workflow?](#What is a workflow?)|
|6 | [What are the four workflow principles?](#What are the four workflow principles?)	|
|7 | [What is a base activity library?](#What is a base activity library?)|
|8 | [What is the function of the Rule Condition Editor dialog box in WF?](#What is the function of the Rule Condition Editor dialog box in WF?)|
|9 | [How can you implement a condition in a workflow?](#How can you implement a condition in a workflow?)|
|10| [What is the difference between a system workflow and a human workflow?](#What is the difference between a system workflow and a human workflow?)|
|1    | [What are XOML files?](#What are XOML files?)|
|2 | [Explain Custom Activities?](#Explain Custom Activities?)|
|3 | [What is a dynamic update?](#What is a dynamic update?)|
|4 | [Which component of WF architecture is responsible to execute each workflow instance?](#Which component of WF architecture is responsible to execute each workflow instance?)|
|5 | [What are runtime services?](#What are runtime services?)|
|6 | [What is a host process?](#What is a host process?)	|
|7 | [Explain why workflows are based on Extensible Models?](#Explain why workflows are based on Extensible Models?)|
|8 | [What is an activity?](#What is an activity?)|
|9 | [What is a runtime engine?](#What is a runtime engine?)|




### What is WPF?
WPF is the latest presentation API by Microsoft Windows. It is 2D and 3D graphic engine. Its capabilities include:-

All the common user controls. For example, check boxes, buttons, sliders etc.

Supports flow and fix format documents

all the functionality of Flash and HTML

Data binding

Multimedia

Animation

### What are the types of documents supported by WPF?

Two types of the documents supported by Windows Presentation Foundation (WPF) are the Flow format and fixed Format document. Flow format document alters the content to fit the screen size while fixed format document present content irrespective of the screen size.
Name the namespace required for working with 3D.
The namespace required for working in 3D is System.Windows.Media.Medi3D.

### Is it right to say that WPF has replaced DirectX?

No, WPF can never replace DirectX. WPF cannot be used to create games with stunning graphics. WPF is meant to be a replacement for windows form, not DirectX.

### What are Freezable objects in WPF?

An object, which has its state locked down, so that it becomes unchangeable, is known as a freezable object. Such objects perform better. It is also safer if they are required to be shared between threads.

### How can the size of StatusBar be increased proportionally?
By overruling the ItemsPanel attribute of StatusBar with a grid. The grid’s columns can be appropriately configured to get the desired result.

### What are dependency properties?

Properties that belong to a specific class but can be used for another are called the dependency properties.

### Why should WPF be preferred over Adobe Flash?

WPF is a more recent technology and thus has the latest development tools. It supports a broader range of programming languages and has a robust control reuse.

### How is Silverlight different from WPF browser application?

One of the major differences is that .NET framework is required for running WPF browser applications on the client machine. But Silverlight runs using only the plug-in. Another point of difference is that applications made in WPF depend on the OS as .NET Framework only runs on Windows. On the other hand, the Silverlight plug-in can be installed on those OSs also, which are not Windows.

Name the methods present in the DependencyObject.

It has three objects, namely:

SetValue

ClearValue

GetValue

### Write about PRISM.

PRISM is a framework for creating complex applications for WPF, Silverlight or Windows Phone. PRISM utilizes MVVM, IC, Command Patterns, DI and Separation of Concerns to get loose coupling.

### Is it possible to use Windows Forms in a WPF application?

Yes, Windows form can be used in WPF. Windows form can appear as a WPF pop. The controls of this Window form can be placed besides WPF controls in a WPF page by utilizing the functions of the WindowsFormsHost control that comes preinstalled.

### Describe CustomControl briefly.

CustomControl widens the functions of existing controls. It consists of a default style in Themes/Generic.xaml and a code file. It is the best way to make a control library and can also be styled or templated.

### Name the common assemblies used in WPF?

PresentationFoundation

WindowsBase

PresentaionCore

### Define Path animations in WPF.

Path animation is a type of animation in which the animated object follows a path set by the Path geometry.

### Can WPF applications be made without XAML?

Yes WPF applications can be created without XAML as using XAML in WPF is a matter of choice.

### What are the types of windows in WPF?

WPF has three types of windows:

Normal Window

Page Window

Navigate Window

### How can elements in a ListBox be sorted?

Sorting can be done by using a property of the ItemsCollection object. ItemsCollection contains an attribute, SortDescriptions, which holds System.ComponentModel.SortDescription instances. Every SortDescription instance defines how the elements should be sorted and indicates if the sort is descending or ascending.

For instance, this code sorts elements of ContentControl on the basis of their word count property:

myItemsControl.Items.SortDescriptions.Add(new SortDescription('WordCount', ListSortDirection.Descending));

### Explain Routed events in WPF.

An event, which can invoke handlers on more than one listeners present in an element tree, instead of the single object which called the event, is known as a Routed event.

### How is MVVM different from MVC?

MVC stands for Model-View Controller and.MVVM stands for Model-View ViewModel.
In MVVM, View Model is used instead of a controller. This View Model is present beneath the UI layer. It reveals the command objects and data that the view requires. It acts like a container object from which view gets its actions and data.
### How is System.Windows.Media.Visual dll utilized in WPF?

It is used whenever a requirement for creating custom user interface arises. It is a drawing object, which gives instructions for making an object. These instructions include opacity etc. of the drawing. The Visual class also bridges the functionalities of WPF managed classes and the MilCore.dll.

### What are the various layout panels in WPF?
They are:

Stack Panel

Grid Panel

Canvas Panel

Dock Panel

Wrap Panel

Name the important subsystems in WPF.

The major subsystems are:

Windows.Controls.Control

Windows.DependancyObject

Windows.FrameworkElement

Windows.Media.VisualsObject

Threading.DispatcherObject

Windows.UIElements

### What does BAML mean in WPF?

BAML is the abbreviation for Binary Application Markup Language. It is nothing but XAML that has been tokenized, parsed and changed into binary form. BAML is a compressed declarative language, which gets loaded and parsed quicker than XAML.

### What is Difference between Page and Window Controls in WPF?
The basic difference is that Window Control presides over Windows Application while Page Control presides over the hosted Browser Applications. Also, Window control may contain Page Control, but the reverse cannot happen.

### What are Attached Properties in WPF?

Attached properties are basically Dependency Properties that allows the attachment of a value to any random object.

### What is the INotifyPropertyChanged Interface?

The InotifyPropertyChanged notifies clients, generally those who are binding, if the value of a property gets changed. It has an event, called PropertyChanged, which gets raised everytime a property of Model object is changed.

### What is the basic difference between Events and Commands in the MVVM Model?

Commands are more powerful and are advantageous to use instead of events. Actions are deeply connected with the event’s source and, therefore, the events cannot be reused easily. But commands make it possible to efficiently maintain multiple actions at one place and then reuse them as per our requirement.

### What is the method to force close a ToolTip, which is currently visible?

It can be closed by setting the tooltip’s IsOpen property to false.

### Write the differences between DynamicResource and StaticResource.

The most basic difference is that StaticResource evaluates the resource one time only, but DynamicResource evaluates it every time the resource is required. And due to this reason, DyanamicResource is heavy on the system but it makes pages or windows load faster

### Explain MVVM pattern.

MVVM pattern divides the UI code into 3 basic parts:

Model – It represents a set of classes, which contain data received from databases.

View – It is the code that agrees with the visual representation of the data.

ViewModel – It is the layer that binds View and Model together. It presents this data in a manner, which is easy to understand. It also controls how View interacts with the application.

### Why are layout panels needed for in WPF?

Layout Panels are needed so that the controls fit screens of different sizes or having different font sizes. If we arrange controls on fixed pixel coordinates, then this model will fail when moved to a different environment. For this reason, Layout panels are necessary.
Question: Write about UserControl in brief.

UserControl wraps existing controls into a single reusable group. It contains a XAML file and a code. UserControl cannot be styled or templated.

### What is the way to determine if a Freezable object is Frozen?

'IsFrozen' property of the object can be used to determine if the freezable object is frozen.

### What is the unit of measurement in WPF?

All measurements are made in device-independent pixels, or logical pixels. One pixel is 1/96th part of an inch. These logical pixels are always mentioned as double, this enables them to have a fractional value too

### What is an adorner?

They are a special kind of FrameworkElement that provide visual clues to the user. They are also used to add handles to elements and give information about the state of a control. Adorners are bound to the UIElement and are rendered on a surface that lies above the element, which is adorned. This surface is called an AdornerLayer. Adorners are mostly placed relatively to the bounded element.

### Explain Serialization?

It is the process of converting the state of an object to stream of bytes.

### Is MDI supported in WPF?

MDI is not supported in WPF. UserControl can be used to give the same functionality as MDI.

### What is XBAP?

XBAP is the abbreviated form of XAML Browser Application. It allows WPF applications to run inside web browsers. Installation of .NET framework on the client machine is a prerequisite for running WPF applications. But hosted applications are not given full admission to the client’s machine and are executed in a sandbox environment. Using WPF, such applications can also be created, which run directly in the browser. These applications are called XBAP.

### In what sense are WPF and Silverlight similar?

Silverlight and WPF are similar in the sense that they both use XAML and share the same code, syntax and libraries.

### How to make a ToolTip appear while hovering over a disabled element?

For this purpose, the ShowOnDisabled property can be used. It belongs to the ToolTipService class.

### How can ListBox be made to scroll smoothly?

ListBox is configured to scroll on an item-by-item basis by default. This is dependent on the height of each element and the scrolling action, thus, giving a rough feeling. Better way is to configure scrolling action so that it shifts items by a few pixels irrespective of their height. This is done by setting the ScrollViewer.CanContentScroll property to 'false'. This will, however, make the ListBox lose the virtualization property.

### Where does the execution start in a WPF application?

WPF applications created in Visual Studio run without a Main method. This is because the applications are special-cased when they are compiled from XAML. That means, Visual Studio attaches a Build Action of ApplicationDefinition to the XAML file. This results in the auto generation of a Main method.

### Can Windows Service be created Using WPF?

No, Windows Services cannot be created using WPF. WPF is a presentation language. Windows services need specific permissions to execute some GUI related functions. Therefore, if it does not get the required permissions, it gives errors.

### What are the different kinds of Routed events in WPF?

There are three types of Routed events in WPF. They are:

Direct – This event can only be raised by the element in which it was originated.

Tunneling – This event is first raised by the element in which it was originated and then it gets raised by each consecutive container in the visual tree.

Bubbling – This event is first raised by the uppermost container in the visual tree and then gets raised by each consecutive container lying below the uppermost one, till it reaches the element it where it was originated.

### Why is it better to wrap items in ComboBoxItem?

It has some important properties like IsSelected and IsHighlighted and also some necessary events like Selected and Unselected. ComboBoxItem is a content control and is thus very useful for adding simple strings to a ComboBox.

### How to get Automation IDs of items in a ItemsControl?

The best way to do this is by setting it Name property as it is utilized for automation purposes by default. But if you require to give an ID to an element, other than it’s name, then the AutomationProperties.AutomationID property can be set as per need.

### Which NameSpace has ‘Popup’ and ‘Thumb’ controls?

The namespace system.windows.controls.primitives has ‘Popup’ and ‘Thumb’ controls.

State the name of the classes, which contain arbitrary content.

Content Control

HeaderedContent Control

Items Control

HeaderedItems Control

### How can command-line arguments be retrieved in a WPF application?

It has some important properties like IsSelected and IsHighlighted and also some necessary events like Selected and Unselected. ComboBoxItem is a content control and is thus very useful for adding simple strings to a ComboBox.

### What is Windows Workflow Foundation (WF)?

Windows Workflow Foundation (WF) is a technology that was first introduced in .NET Framework 3.0. WF consists of a programming model, a workflow runtime engine, workflow designer, a rules engine, and tools to quickly build workflow-based applications on Windows. WF facilitates the separation between the business process code and the actual implementation code.

### What are the components of WF 4.0?

WF consists of several components that work together to create desired workflow. The components of WF are given as follows:

Workflows and activities

Base activity library

Custom activities

Host process

Activity data model

Runtime engine

Runtime services

### What is the advantage of using WF?

By using WF we can separate the business logic of the application from the execution components. This way we can build a clearer and 
more manageable application.

### What are the different types of work flow?

There are mainly three types of work flow:

a)Sequential workflow

b)State Machine workflow

c)Rules-driven Workflow

###  What is Sequential workflow?

A Sequential workflow is the one where steps of the work is done in sequence from start to finish. In a Sequential workflow ,from beginning to end,the workflow engine initiates each step.

### What is State Machine workflow?

A State Machine workflow is the one that is initiated by external events and user interaction, unlike Sequential workflow which is initiated by workflow engine. A State Machine workflow thus stores state between events.

### What is Rules-driven Workflow?

This is a type of work flow implemented based on Sequential or StateMachine workflow. But there are additional rules that dictate the progress of the workflow.

### How can we define and edit a workflow?

We can define a work flow using XAML.work flow can also be defined in code using languages like C#.NET,VB.NET etc.Once defined we can edit the work flow using Visual Studio.

### How does WF allows the workflow to update the Host Application?

The host application can be updated by raising events in WF runtime to which the host application has subscribed. This way we can start or stop workflow instance.

### What is a workflow?

A workflow is a collection of actions (called activities) that presents the model of a process. A workflow provides a way to describe the order of the execution of a long running process and relationships between different activities. Multiple instances of a workflow may be active at any given moment in an application.

### What are the four workflow principles?

According to Microsoft, there are four major principles that explain the behavior and working of workflows. Developers can use these principles while developing workflow-based applications. The four principles are as follows:

Workflows help in coordinating the work performed by people and software.

Workflows are long-running and stateful.

Workflows are based on extensible models.

Workflows remain transparent and dynamic throughout their lifecycle.

### What is a base activity library?

The base activity library is a collection of activities used to create workflows.

### Explain the concept of Bookmarks in WF 4.0.

In WF 4.0, a bookmark is a mechanism that enables an activity to wait for an input without interrupting a workflow thread. When an activity signals that it is waiting for the input from a user, it can create a bookmark. A bookmark is created by using the BookmarkOptions class. This class provides the following bookmark types:

None - Represents a bookmark that can be resumed exactly once. This is the default bookmark type.

MultipleResume - Refers to a bookmark that you can resume multiple times.

NonBlocking - Refers to a bookmark that does not block the functioning of the workflow.

### What is the function of the Rule Condition Editor dialog box in WF?

You can create and modify declarative rule conditions by using the Rule Condition Editor dialog box.

### How can you implement a condition in a workflow?

You can implement a condition by using either of the following ways:

By creating a rule condition - Specifies that you can implement conditions either directly in code or by using a tool, called the Rule Condition Editor. Rule conditions are stored in a separate Extensible Markup Language (XML) file. When a rule condition occurs in a workflow, the expression in a condition is evaluated and a Boolean value is returned.

By creating a code condition - Refers to defining a condition directly in code. A code condition can be created by writing a method in the code. The method contains code for the condition and returns a Boolean value. 

### What is the difference between a system workflow and a human workflow?

A system workflow is a workflow that is developed to automate interactions among applications. Such workflow is usually static and predictable. On the other hand, a human workflow is a workflow that coordinates interactions of applications with people. As human workflows involve both software and people, they need to be more flexible than system workflows.

### What are XOML files?

WF provides developers a declarative way to create workflows by using extensible Application Markup Language (XAML). The files used to store such workflow markups are known as extensible Object Markup Language (XOML) files.

### Explain Custom Activities.

In addition to the standard activities available within the base activity library, you can create new activities to meet specific business needs. Creating custom activities may be required to support a particular application that you want to integrate with WF. Custom activities are generally created through attributes and inheritance. You can create two types of custom activities, base and composite. You can create basic custom activity by inheriting the Activity class and custom composite activity by inheriting the compositeActivity class or a derived type.

### What is a dynamic update?

Dynamic update is a powerful feature of WF that describes the ability of WF to modify the execution path of a running workflow. This feature is used in circumstances that call for extraneous behavior that was not modeled by the original workflow developer.
Which option do you need to select for the Condition property, if you want to create a code condition?
You can select the Code Condition option to create a code condition.

### Which component of WF architecture is responsible to execute each workflow instance?

WF runtime engine is responsible to execute each workflow instance.

### What are runtime services?

Runtime services consist of predefined and user-defined classes that are available to the workflow runtime engine during execution to customize the behavior of workflow runtime. Some of the runtime services available in WF 4.0 are as follows:

Scheduling services - Enable creating and scheduling new workflow instances for execution.

Work batch services - Enable behavior to maintain a stable and consistent execution environment.

Persistence services - Enable you to save or restore the state of a running workflow for later use. You can restart the saved workflow anytime in future, even after weeks of inactivity.

Tracking services - Enable you to monitor the state of the workflows. This is particularly useful when you have multiple workflows active at the same time (for example, in a shopping cart application).

Timer service - Manages the timing required by the DelayActivity activity.

Transactions services - Provide the transaction support needed for data integrity.

Data exchange services - Manage custom communication services.

Threading services - Administer physical threads used to execute workflow instances.

### What is a host process?
A host process is an executable program that hosts a workflow. It may be a Windows Forms application, a Web application, or a Web service application. You can use Web services in the host process or remoting to enable other applications to communicate with the workflow.

Write the steps that are involved in the sequential workflow, by default.

By default, a sequential workflow has only two steps:

i.Start

ii.Finish 

### Explain why workflows are based on Extensible Models.

Workflows serve the purpose of automating business processes. Now, since each type of business has a wide range of problems; therefore, a workflow platform needs to be extensible. WF provides you with a set of base activities, such as If Else, Code, and Delay, to build a workflow. You can extend these activities or build new activities to meet your requirements. Besides activities, you can also extend services, such as tracking, management, and persistence, provided by the runtime engine.

### What is an activity?

In Windows Workflow Foundation 4.0, an activity is the basic unit of composition and execution of a workflow. Each activity in a workflow consists of its own variables and arguments and is a subclass of the Activity class. These activities provide facilities for flow control, exception handling, data persistency, loading or unloading workflows, tracking, and transaction flow.

### What is a runtime engine?

A runtime engine of WF provides the basic functionality to execute and manage the workflow lifetime. It runs within the host process and is responsible for executing each workflow instance. A host process can interact with multiple runtime engines at a time, where each engine executes multiple workflow instances. The host process interacts with runtime engine by using any of the following classes:

WorkflowInvoker - Invokes a workflow as its method.

WorkflowApplication - Controls the execution of a single workflow instance explicitly.

WorkflowServiceHost - Hosts the workflows and allows sending and receiving messages among various instances of workflows.
