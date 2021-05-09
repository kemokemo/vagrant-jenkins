# vagrant jenkins

This repository is for practices that use vagrant to easily build a Jenkins-enabled VM.  
I referred to the following article.

- https://rdarida.medium.com/installing-jenkins-on-localhost-with-vagrant-8aa59761bec
- https://www.jenkins.io/doc/book/installing/linux/#debianubuntu

## Usage

```sh
vagrant up
```

After Jenkins has started successfully, access to `http://localhost:9000`.  
You should see "Administrator password" in the standard output, so use it to log in.

