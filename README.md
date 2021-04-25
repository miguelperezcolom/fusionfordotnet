# Fusion Port For .Net

This project aim is to build a port of Vaadin Fusion for .Net.

As far as I have seen, Vaadin's Fusion project aims to generate a typescript client for java rest apis (defined with the jax-rs specification).

So, the project should be quite easy and straightforward. In java you just need to create an annotation processor and use some java reflection to build the TS code and, if you want, call npm to package and publish at the npm registry. In .Net we should easily be able to do the same. You know, it's just some meta-programming/code generation ;).

When I faced this same problem before (consuming java rest apis from the client side) I peferred to rely on Swagger, integrating it inside our build pipeline, and it run quite smoothly. Today I would say that, when it comes to join together the frontend and backend teams, I would just rely on Swagger to define the apis and let both team (frontend and backend) create their client/server side code from Swagger itself. Anyway, we are now talking about the use case where you are creating the api from the server side ;).

I must also say that one of the requisites for this project is to be done using the Community Friday (CF) time that we have at Vaadin. I joind the Vaadin company at 2021, January 1st, and the company gives you some time (CF) for doing this kind of open source projects for helping the community. So, this project must be resolved using that time.

## The plan

The plan is the same as for every project:

I understand the first step will be to dig deeper inside the Fusion project, in order to fully understand the scope and the functionality which it is offering. That should allow me to define the requisites / acceptance criteria for this project.

As soon as the requisites are ready, I will do the analysis and design of the solution. Here I presume that perhaps I will open both approaches (generating the ts code from .Net and relying on Swagger).

Then just write the code and unit tests, create the CI pipeline using the Github Actions for publishing the artifacts at NuGet, create the documentation inside the project wiki, create a demo website, .... I will try to do everything inside Github (issue tracking, kanbans, CI, ...). 

At the end, when the first release is out, do some marketing stuff to let the people know about the project.

## Conclusion

So, that's it. Quite a beautiful and tiny project. The only problem is that I'm not sure if I will be able to steak to the CF time, and I will finish working on it during my free time ;)

## Documentation

- [010. Analysis](https://docs.google.com/document/d/1FaDw_clCTbwD4afMGLMg4LuV-GCynWqcbN4N5j8Oko8/edit?usp=sharing)






