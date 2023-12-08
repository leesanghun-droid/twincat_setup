# twincat_setup

1. install visual studio 2017

2. install TC31-FULL-Setup.3.1.4024.53

==> select visual studio 2017 option both

3. applay lincense

4. run visual studio 2017 and project create
    ==> xml format

5. add task

6. add isolate core 2ea

7. Enable C++ Debugger

8. C++ ADD Project
==> TwinCAT Driver Project 
==> TwinCAT Module Class with Cyclic IO
==> ADD C++ Modules ( Module1)
==> Module1 setup => Context Task = Select made task

9. Activate configuration
==> error
    ==> Error starting Untitled1 server. Win32 Error: 577
    ==> solution => add certification

10. certification
==> TwinCAT => Software Protection == > Create OEM Certificate
==> select Sign TwinCAT C++ executable ==> make save or import ( C:\TwinCAT\3.1\CustomConfig\Certificates )

11. C++ Project add certification
==> 구성 속성 => Tc Sign => TwinCAT signing Select YES => TwinCAT Certificate Name password input

12. Activate configuration
==> error
    Error starting Untitled1 server. Win32 Error: 87 