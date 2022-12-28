
# SlfHstd-docker-compose-stacks

A brief description of what this project does and who it's for:

I got sick of blowing away my stuff and having to build everything from scratch everytime. Most of this stuff is inspired by a need or, by borrowing ideas from other people for my own needs but... it's totally cool if it helps you out. 



## Environment Variables

Check the following files for the the variables that you might have to change. WARNING - THERE BE DRAGONS!


## Deployment

To deploy any compose stack, cd into the stack you want to create, make sure you update any variables (dont worry... they're pretty obvious if they are any), then run

```bash
  docker compose up -d # Stands up the stack and creates the resources for them if they don't exsist (assuming all permissions are corect)
  docker compose down  # Tears down the stack and the resources it creates from the folder it's stood up from
```




## Acknowledgements

I have to thank the work I do (DevOps) and my quests for knowledge and self-improvment as well a touch ot Parkinson's Law 
 
 - [Awesome-Compose](https://github.com/docker/awesome-compose)
 - [Awesome-Lists](https://github.com/sindresorhus/awesome)
 - [Fleet](https://fleet.linuxserver.io)
 - [Awesome Slf Hosted Blogs](https://lmgtfy.app/?q=how+to+run+and+instal+docker+and+docker+compose)



### README
This magnificant README was generated with ❤️ from [Awesome Readme Template Generator](https://readme.so/)