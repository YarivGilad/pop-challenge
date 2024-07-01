## Countries population challenge

### Installation
1. Clone the repository
2. cd into the directory
3. Run `npm install` to install the dependencies
4. Run `npm run dev` to run the program
5. Notice you'll need at least node version 19 to run the program in watch mode...

### Instructions
1. First - translate the first two functions **getCountryPopulation()** and **manual()** to async functions
2. Second - Given the array of countries, call the **getCountryPopulation()** function multiple times
once for each country and display the results like this for example:    
```log.magenta(`The population of France is 66977107`)```
3. Figure out how you can manage the calls both in `Sequence` as well as in `Parallel` ;    
`Sequence` means we will only start the subsequent request after the previous had completed.    
`Parallel` means we do not wait for the previous request to finish. each request will finish in its own time
                and we will print out the results to the console only when all requests have been completed
4. Use Vanilla JavaScript in this challenge
5. In both cases, you should print out the populations of the countries **precisely** in the same order as they appear in the countries' array
6. You should ```console.log('all done!')``` after all populations were printed for all countries.
7. You can use any Promise method in conjunction with async/await to achieve the desired result - but not the .then() method.