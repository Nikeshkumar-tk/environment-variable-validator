# environment variable validator 

  

Env validator for validating the environment variables in your application

  

## Installation

  

### Using npm

  

If you prefer to use npm, open your terminal and run the following command:

    npm install environment-variable-validator


### Using Yarn

  

If you prefer Yarn, open your terminal and run the following command:

    yarn add environment-variable-validator
    
## How to use
### Node js

```typescript
import { validate_env_variable } from 'environment-variable-validator'

//Passing env variables and its types for validation
validate_env_variable({
DATABASE_URL: 'string'
})
 
