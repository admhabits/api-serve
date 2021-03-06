## Api Services: React + Node JS (Express) + MySQL

This example shows how to leverage [Okteto](https://github.com/okteto/okteto) to develop a React + Node JS (Express)  + MySQL Sample App directly on Okteto Cloud. The Sample App is deployed using a [kustomize](https://github.com/okteto/polling/blob/master/okteto-pipeline.yml). It creates the following components:

- A *React* based **frontend**.
- A splp as **api**.
- A [MySQL](https://www.mysql.com/) database.

## Tutorial

- Deploy the **Api Portal Services SPLP** on your personal namespace by clicking on the following button:

<p align="center">
<a href="https://cloud.okteto.com/deploy">
  <img src="https://okteto.com/develop-okteto.svg" alt="Develop on Okteto">
</a>
</p>


- To develop on the **splp** component:

```
    $ okteto up -f splp/okteto.yml
      ✓  Development container activated
      ✓  Files synchronized
         Namespace: yournamespace
         Name:      api
         Forward:   
                    8080 -> 8080

    Welcome to your development environment. Happy coding!
    githubid:nodejs okteto> npm run start:dev

```
