# error-js

try {

  const myError = new Error('This is a custom error message');
  throw myError;


} catch (error) {


  console.error(error.message);
  console.error(error.stack);
  console.error(error.name);
  
  
}
