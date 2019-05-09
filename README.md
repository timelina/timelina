# timelina

1. Make project serverless with ng-toolkit/serverless package.

1.1. Links to documentation and tutorials
    https://coursetro.com/posts/code/155/Angular-6-SEO-Tutorial-from-Scratch---It's-Super-Simple-Now!
    
    https://github.com/maciejtreder/ng-toolkit
    
    https://medium.com/@maciejtreder/angular-serverless-a713e86ea07a
    
    https://www.npmjs.com/package/@ng-toolkit/serverless

1.2. 1st package need to installed is: @ng-toolkit/universal
    ng add @ng-toolkit/universal

    This package installation will add bunch of files in project root folder and in ..\src also.

Now instead of ng serve we build and run like so:
1.3. Build project    
    npm run build:prod

1.4. Run project locally.
    npm run server

1.5. Site can be opened at http://localhost:4000

1.6. Adding 2nd package which allows deploy project to firebase (aws).
    ng add @ng-toolkit/serverless --provider firebase --firebaseProject timelinacom
    
1.7. Run deployment process.
    sudo npm run build:prod:deploy


1.8. If https://timelina.com/ shows web site fine and for SEO we see source code as HTML then commit changes.


2. Add Angular Material and make base design pattern with navigation and dashboard.

