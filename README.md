# angularstarter

This automated project was generated by boo.

# Run This

Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

# Code scaffolding

Run ng generate component component-name to generate a new component. You can also use ng generate directive|pipe|service|class|guard|interface|enum|module.

# Build

Run ng build to build the project. The build artifacts will be stored in the dist/ directory. Use the --prod flag for a production build.

# Run the below in the same order

1  curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -

2  sudo apt-get install -y nodejs

3  mkdir ~/.npm-global

4  export PATH=~/.npm-global/bin:$PATH

5  source ~/.profile

6  npm config set prefix /usr/local

7  sudo chown -R $USER /usr/local

8  npm install -g @angular/cli

9  npm install -g pm2

10 pm2 start npm — start
