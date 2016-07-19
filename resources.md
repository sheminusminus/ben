#nodejs, npm, and expressjs

you should be able to test any/all of this on your own machine first, but good practice to test it remotely to make sure everything works as expected

###npm module tutorial
- you don't have to actually publish anything, but strongly recommend doing this to understand creating node projects:
[npm modules](https://quickleft.com/blog/creating-and-publishing-a-node-js-module/)

###to download the foundation library through npm and add it to your project's package.json file:
1. `cd your-project-directory`
2. `npm install foundation-sites -S`

###codeschool tutorial on expressjs (they're really corny but typically good)
[building blocks of expressjs](https://www.codeschool.com/courses/building-blocks-of-express-js)

###codeforgeek's expressjs walkthrough
[express complete tutorial](https://codeforgeek.com/2014/10/express-complete-tutorial-part-1/)

###expressjs tutorial, less comprehensive but goes over file uploads
[nodejs and express framework](http://www.tutorialspoint.com/nodejs/nodejs_express_framework.htm)

###mysql package for node (*should* be the same one used in the express/mysql tutorial)
[mysql npm package](https://www.npmjs.com/package/mysql)

###expressjs + mysql connection
[basic express to mysql connection](https://expressjs.com/en/guide/database-integration.html#mysql)

###testing your app + database with user loads
[user testing for nodejs and musql](https://codeforgeek.com/2015/01/nodejs-mysql-tutorial/)

###the ec2/nodejs setup tutorial
[ec2 and nodejs](https://codeforgeek.com/2015/05/setup-node-development-environment-amazon-ec2/)

##ec2 alternative

if you have trouble configuring anything on ec2, or want more control over your box-

super awesome alternative is digitalocean, which gives you 100% control, lets you mess with literally anything, and has amazing resources (i use DO almost exclusively)

you can create and destroy droplets (instances) at whim, which is nice for experimenting

- for digitalocean, the $5/month droplet option will be more than adequate
- for the OS, ubuntu 14.04 (from new york 1, 2, or 3, doesn't matter) gives you the most leeway + resources available
- $10 in digitalocean credit (so like 2 free months) if you sign up via this link: [get creditz yo](https://m.do.co/c/41f60e0a2ecd)
- their ubuntu setup guide: [initial ubuntu setup](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-14-04)
- **using ubuntu, nodejs, sockiet.io, express framework, and client-side javascript all together: [the whole shebang!](https://www.digitalocean.com/community/tutorials/how-to-install-express-a-node-js-framework-and-set-up-socket-io-on-a-vps)**

digitalocean's ubuntu tutorials will apply to almost any ubuntu machine, so [their community section](https://www.digitalocean.com/community) is a goldmine whether you use them or not
