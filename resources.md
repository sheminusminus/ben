you should be able to test any/all of this on your own machine first, but good practice to test it remotely to make sure everything works as expected

###codeschool tutorial on expressjs (they're really corny but typically good)
https://www.codeschool.com/courses/building-blocks-of-express-js

###codeforgeek's expressjs walkthrough
https://codeforgeek.com/2014/10/express-complete-tutorial-part-1/

###expressjs tutorial, less comprehensive but goes over file uploads
http://www.tutorialspoint.com/nodejs/nodejs_express_framework.htm

###mysql package for node (*should* be the same one used in the express/mysql tutorial)
https://www.npmjs.com/package/mysql

###expressjs + mysql connection
https://expressjs.com/en/guide/database-integration.html#mysql

###testing your app + database with user loads
https://codeforgeek.com/2015/01/nodejs-mysql-tutorial/

##ec2 alternative

if you have trouble configuring anything on ec2, or want more control over your box-

super awesome alternative is digitalocean, which gives you 100% control, lets you mess with literally anything, and has amazing resources (i use DO almost exclusively)

you can create and destroy droplets (instances) at whim, which is nice for experimenting

- for digitalocean, the $5/month droplet option will be more than adequate
- for the OS, ubuntu 14.04 (from new york 1, 2, or 3, doesn't matter) gives you the most leeway + resources available
- $10 in digitalocean credit (so like 2 free months) if you sign up via this link: https://m.do.co/c/41f60e0a2ecd
- their ubuntu setup guide: https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-14-04
- **using ubuntu, nodejs, sockiet.io, express framework, and client-side javascript all together: https://www.digitalocean.com/community/tutorials/how-to-install-express-a-node-js-framework-and-set-up-socket-io-on-a-vps**

digitalocean's ubuntu tutorials will apply to almost any ubuntu machine, so their community section is a goldmine whether you use them or not
