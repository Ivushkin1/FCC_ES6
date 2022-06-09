# FCC_ES6

import* as myMathModule from "./math_functions.js";                   // import all


const makeServerRequest = new Promise((resolve, reject) => {
  let responseFromServer = false;
  if(responseFromServer) {
    resolve("We got the data");
  } else {  
    reject("Data not received");                                            //PROMISE
  }
});

makeServerRequest.then(result => {
  console.log(result);
});
makeServerRequest.catch(error => {
   console.log(error);
});


