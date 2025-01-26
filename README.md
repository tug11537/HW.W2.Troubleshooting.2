# Troubleshooting 2 | MUST 4707

## Finding Errors in existing code and fixing them

In this assignment you will update the file `script.js` and commit it to your assignment repository. Your updated version of `script.js` should run without any errors. The object `myWinterCoat` should have all of the proper syntax required of an object. If it does, it will export properly and your code will pass all of the tests.

### Troubleshooting

Troubleshooting is the process of identifying, diagnosing, and resolving issues or problems in a system, device, software, or any complex situation. It involves systematically analyzing the symptoms, investigating potential causes, and implementing solutions to restore normal functionality or achieve the desired outcome. Troubleshooting is a critical skill used in various fields, including technology, engineering, and everyday problem-solving, to address and fix problems efficiently.

### Accessing the Assignment Materials
1. Navigate to the assignment repository in the course [GitHub organization](https://github.com/MUST4707)
2. Click on the green `Use this template` button in the top right corner.
3. Choose 'Create a new repository'
4. Set up the repo name under your account.
5. Click `Create repository`

*You should now be at your own personal repository with the assignment materials.*
6. Click on the green `<> Code` button and select `Open with GitHub Desktop

*You should now be in your GitHub Desktop application that has a pop up window called 'Clone a Repository'*

7. Make sure the local path is where you would like to save this repo.
8. Hit `Clone`
9. You should be able to now click the `Open in Visual Studio Code ` button or navigate to your files and open the folder in Visual Studio Code.
10. After you finish working on your project please return to GitHub Desktop and
11. Commit your changes to the `master` (don't to add a summary description)
12. Click on the `Push Orgin` to sync your commit with the GitHub cloud.


### Task Description

1. The provided `script.js` contains an object called `myWinterCoar` but there are some coding errors
2. Figure out what is wrong with the code and fix it!

3. After fixing the errors in the code, make sure it meets the requirements listed below and pass the provided tests.

### Coding Instructions

You will edit your code  in `script.js`:

```javascript
const myWinterCoat = {
           model: "650 Down Jacket",
           version: 2.0,
           color: "black,
           brand: {
              name: "REI",
              website; "https://rei.com",
              phone: "+18004264840",
              headquarters: {
                 city: "Sumner",
                 state: "WA",
                 dateFounded: 1938
              }
           },,
        hadHood false,
        bestUse: ["Casual", "Hiking"],
        fabric: "Recycled nylon taffeta",
        liningFabric: "Nylon taffeta",
        insulated: true
        insulationType: "down",
        insulation:	"650-fill-power down",
        warmth: "Warmer",
        weight: {
            amt 10.8,
            unit: "ounces"
        }
}

```

---

### Testing Your Work (Using VS Code and your Browser)
1. Make sure you have saved all of your files, then click on the `index.html` file.
2. Click on "Go Live"
3. Once the browser window opens with the assignment webpage, open the Javascript Console
4. Run the following test to make sure there are no errors.
   1. Test 1: `myWinterCoat`
      - the result should be `{model: "650 down jacket" ...... and so on`
   2. Test 2:`typeof myWinterCoat`
      - result: `'object'`

*If any of the above commands return an error or an unexpected result please return to you code and update to fix the error. Repeat this process over and over until their are no errors*


### Submission Steps
1. Upload your `script.js` to the Canvas assignment.

