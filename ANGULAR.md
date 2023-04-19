To install the Angular CLI, open a terminal window and run the following command:

npm install -g @angular/cli

On Windows client computers, the execution of PowerShell scripts is disabled by default. To allow the execution of PowerShell scripts, which is needed for npm global binaries, you must set the following:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

1. Run the CLI command ng new and provide the name my-app, as shown here:</br>
    ng new my-app

2. Run the application </br>
    cd my-app </br>
    ng serve --open

    The --open (or just -o) option automatically opens your browser to http://localhost:4200/.