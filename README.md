# Bugs-and-their-solution
Development bugs and their solution


Bug 1 : ng.ps1 cannot be loaded because running scripts is disabled on this system. For more information, see 
about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170

Solution : ClientApp> Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope CurrentUser 
           ClientApp> ng serve
