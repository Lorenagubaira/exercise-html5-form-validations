<!--hide-->
# HTML5 Form Validations
<!--endhide-->

After building the HTML and CSS for this form, we need to make sure it prevents the user from submitting a form with the wrong information or format, in web development we call that: Form Validations, you can read more [here](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)

To prevent a form submission, we have to listen to the "submit" event that is triggered by the form itself when the user presses either: the enter/return key or the submit button.

Here is a little more about preventing an event from occurring: [https://www.youtube.com/watch?v=I_fVO_NzT2g&t=401s](https://www.youtube.com/watch?v=I_fVO_NzT2g&t=401s)

![Form Validations Preview](https://github.com/breatheco-de/exercise-html5-form-validations/blob/master/preview.gif?raw=true)

<onlyfor saas="false" withBanner="false">
 
## 🌱  How to start this project

Do not clone this repository.

The first step to start coding is cloning the [vanillajs boilerplate](https://github.com/4GeeksAcademy/vanillajs-hello) on your local computer or opening it using gitpod.

a) If using Gitpod you can clone the boilerplate by [clicking here](https://github.com/4GeeksAcademy/vanillajs-hello).

b) If working locally type the following command from your command line: `$ git clone https://github.com/4GeeksAcademy/vanillajs-hello`.

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

</onlyfor>

## Instructions

After the user submits the form:

1. Make sure to stop the flow of the submission using `preventDefault()`, [here is a little bit more about preventDefault()](https://www.youtube.com/watch?v=3SNyh57XSIA).  
2. After preventing the submission, make sure all the input values are correct and properly formatted.  
3. If there are one or more inputs with an invalid value, show a clear error on the top of the form with a very explicit message about what happened.  
4. Change the background color of the relevant inputs (the ones with incorrect data).  

## What to do if you are stuck?

Don't get frustrated and ask for help! After trying on your own for 20 min, it is time to stop working and ask for help.

## 🤠 Feeling Confident?

This additional requirement is not mandatory to complete the project:

 Make the form errors show on top of each input instead of on the top of the form, that way the user will understand faster what the problem is about.
