
# SlfHstd-docker-compose-stacks

A brief description of what this project does and who it's for:

I got sick of blowing away my stuff and having to build everything from scratch... everytime. Most this stuff is inspired by a need, then by borrowing ideas from other people.



## Environment Variables

Check the following files for the the variables that you musg change:


## Deployment

To deploy any compose stack from this project, cd into the stack you want to create (beware, there be dragons lurking), make sure you update any variables (dont worry... they're pretty obvious if they are), then run the floowing command

```bash
  docker compose up -d # Stands up the stack and creates the resources for them if they don't exsist (assuming all permissions are corect)
  docker compose down  # Tears down the stack and the resources it creates from the folder it's stood up from
```




## Acknowledgements

Mostly born out of boredom and my quest for knowledge, I borrowed a lot of ideas for this from work and legit DevOps blogs 
 
 - [Awesome-Compose](https://github.com/docker/awesome-compose)
 - [Awesome-Lists](https://github.com/sindresorhus/awesome)
 - [Fleet](https://fleet.linuxserver.io)
 - [Awesome Slf Hosted Blogs](https://lmgtfy.app/?q=how+to+run+and+instal+docker+and+docker+compose)



### README
This magnificant README was generated with ❤️ from [Awesome Readme Template Generator](https://readme.so/)