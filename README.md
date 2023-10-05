# Lab_mst11


<!DOCTYPE html>
<html>
<head>
    <title>Signup Page</title>
    <style>
        #signup{
            display: flex;
            justify-content: center;
            padding-top: 30px;  
        }
        form{
            text-align: center;
            margin: 2rem;
        }
        input{
            margin: .7rem;
            height: 1.7rem;
            width: 16rem;
        }
        .SignForm{
            border: 2px solid black;
            border-radius:10px;
            width: 500px;
            height: 500px;
        }
        h1{
            text-align: center;
        }

        button{
            height: 2rem;
            width: 16rem;
            border-radius: 1rem;
            border: none;
            font-family: monospace;
            columns: white;
            background-color: crimson;

        }
        button:hover{
            color: white;
            background-color: black;
            text-align: center;
            cursor: pointer;
        } 
    </style>
</head>

<body>
    <div id="signup">
    <div class="SignForm">
    <h1>Signup</h1>

        <form action="/signup" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required><br><br>

            <label for="username">Full Name:</label>
            <input type="text" id="fullname" name="fullname" required><br><br>

            <label for="email">Email Id:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required><br><br>

            <button type="submit">Sign Up</button>
            <p>Don't have an account <a href="LoginForm.html">Sign In</a></p>
        </form>
    </div>
</div>
</body>

</html>







**Explain**



The provided code appears to be an HTML snippet for creating a simple signup form for a website. Let's break down the code step by step:

<head>: This is the opening tag for the head section of the HTML document. The head section typically contains metadata and links to external resources such as stylesheets and scripts. However, in the provided code, it is incomplete as it lacks necessary elements like <title> and <meta> tags.

<body>: This is the opening tag for the body section of the HTML document. The body section contains the visible content of the web page.

<div id="signup">: This is a <div> (division) element with the ID attribute set to "signup." It is used to create a container for the signup form.

<div class="SignForm">: This is another <div> element with the class attribute set to "SignForm." It is nested within the "signup" <div>. It is likely used for styling purposes or to group related elements.

<h1>Signup</h1>: This is an <h1> (heading 1) element that displays the text "Signup." It is the main heading for the signup section.

<form action="/signup" method="post">: This is an HTML form element that defines the start of a form. It has two attributes:

action="/signup": This specifies the URL where the form data will be sent when the user submits the form. In this case, it will be sent to "/signup," which suggests that there should be a server-side script to handle the form submission at that URL.
method="post": This specifies the HTTP method to be used when submitting the form. In this case, it's set to "post," which is commonly used for form submissions to send data securely.
Inside the form, there are several <label> and <input> elements:

<label for="username">Username:</label>: This is a label element associated with an input field. The "for" attribute with the value "username" is used to connect this label to an input field with the same "id."

<input type="text" id="username" name="username" required>: This is an input field for entering a username. It has several attributes:

type="text": Specifies that this is a text input field.
id="username": Provides a unique identifier for the input element.
name="username": Specifies the name of the input element, which will be used when processing form data on the server.
required: Indicates that this field is required and must be filled out by the user.
Similar <label> and <input> elements are provided for "Full Name," "Email Id," and "Password."

<button type="submit">Sign Up</button>: This is a submit button within the form. When clicked, it will trigger the form submission to the URL specified in the action attribute.

<p>Don't have an account <a href="LoginForm.html">Sign In</a></p>: This is a paragraph element containing text and a hyperlink. It suggests that if the user doesn't have an account, they can click the "Sign In" link, which will likely take them to a login page (LoginForm.html).

</form>: This is the closing tag for the form element, indicating the end of the form.

</div>: These are closing </div> tags that close the "SignForm" and "signup" <div> containers.

</body> and </html>: These are closing tags for the body and HTML documents, respectively, indicating the end of the HTML structure.

In summary, this code creates a signup form with fields for a username, full name, email, and password. When the user submits the form, the data is sent to the "/signup" URL. Additionally, there is a link to a login page ("LoginForm.html") for users who already have an account. However, some essential elements in the HTML structure (such as the <title> tag in the head section) are missing, and the server-side processing of the form data is not included in this code snippet.



**Link of output**


(https://docs.google.com/document/d/13mVuAyG5sHXc-3ro35hQ9_nRvXZpPM_CMTAC4yDfidc/edit)https://docs.google.com/document/d/13mVuAyG5sHXc-3ro35hQ9_nRvXZpPM_CMTAC4yDfidc/edit
