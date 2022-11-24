**Prereqs**

Node v14.x, npm

`npm i -g serverless serverless-offline`

`npm i -g @nestjs/cli`

Something else might be needed may be, but its only a quick instruction.

**Try to run project as App**

`nest start`

Then open `http://localhost:3000` and you should be able to see "Hello world".

**Try to run project as Lambda**

`npm run build`

`serverless offline start`

"Can not GET /" - why?!
