# frameworks
Some frameworks for servers side

## Some remarks
[Here you can find some benchmarks](https://www.techempower.com/benchmarks/#hw=ph&test=composite&section=data-r22)
Some scores:
- express is placed at 130 place
- fast api is 86
- django is 143
- koa is 117

If you look for performance you should not use python frameworks


## Fastapi python

If you want to quicly develop some application for your own use you can take advantage of [fastapi](https://fastapi.tiangolo.com/)
As the authors say: "FastAPI is a modern, fast (high-performance), web framework for building APIs with Python based on standard Python type hints". DEfinitely it is very convenient to use, e.g. documentation is generated automatically, moreover, there is interactive api which helps you test requests to your api. You can find [tutorial here](https://fastapi.tiangolo.com/tutorial/)


## Koa

This [framework](https://koajs.com/) is very similar to the express (no suprise because it is designed by the team behind Express) one but is slightly faster according to the mentioned benchmark. It uses concepts of `api.context` which encapsulates responses and requests.  

## GraphQL

- [tutorial](https://graphql.org/learn/)
- [running with express](https://graphql.org/graphql-js/running-an-express-graphql-server/)
- [why use graphql](https://www.apollographql.com/blog/why-use-graphql)


## AskQL

A next step after GraphQL and [Serverless](https://github.com/serverless/serverless)
- [github](https://github.com/CatchTheTornado/askql)
- [example](https://github.com/YonatanKra/askql-demo)
- [playground](https://cli.askql.org/#)


## H2O

- [github](https://github.com/h2o/h2o/wiki)
- [examples](https://github.com/h2o/h2o/wiki/Projects-and-Examples-using-libh2o) used by e.g. [silicon](https://github.com/matt-42/silicon) ([what is silicon](https://siliconframework.org/))

## HyperExpress
  This framework has api similar to express one but has c++ bindings so if it comes to the performence it is comparable to best ones.
- [github](https://github.com/kartikk221/hyper-express)
- [examples](https://github.com/kartikk221/hyper-express/blob/master/docs/Examples.md)


# Code analysis

- Snyk Code: An expert-curated, AI-powered TypeScript code checker that analyzes your code for security issues, providing actionable advice directly from your IDE to help you fix vulnerabilities quickly.
- DeepCode: A static code analyzer that uses AI to identify potential issues in your code, including bugs, security vulnerabilities, and performance bottlenecks. It supports multiple programming languages, including TypeScript.
- Codacy: An AI-powered code review tool that provides automatic code review for over 30 languages, including TypeScript. It integrates with GitHub, Bitbucket, and GitLab, enabling developers to find and fix issues directly from their repositories.
