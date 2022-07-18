# formik.challenge.io

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <title>React App</title>
    <link rel='stylesheet' type='script' href='
  </head>
  <body>

    <div id="root"></div>
                                               <script>
import React from 'react';
import ReactDOM from 'react-dom';
import { Formik, Field, Form } from 'formik';

const Basic = () => (
  <div class= "justify-content-center">
    <h1>CONTACTING</h1>
    <h2> VOLOSKYR, SVRYEIDA KURDRADISH</h2>
    <h3> <p>REGARDING, these soaps which pour having been rather late the month of May, it's origins being from the Western Siberian Plains post abolition, having graced the bath halls of late TSARESS SHA'HARINA A. DOTYAVICH through the coldest months of these northern climes. In mourning, it's long awaited delivery accompanied by such cold & blustery winds alongside the folding of 1,000 paper cranes & tired hands. For a great many days the weather would never permit travel across the Pacific Tundras. </p>
      
      <p>Should you have been at all " put-off " by the delay in arrival time, please know the professional Bureau of Telekinetic Affairs has been informed. </p></h3>
     <h6><p>Please be aware that said soap samples in their laboratory preparation have been well freeze dried disregarding departure times. These processes have in no way changed due to International Standards of  Trading. These conditions have in no way changed due to International Standards of Storing.
       </p></h6>
       <h3> Have you been the recipient of these soaps? Have your soaps been lost in the mail? Should you have been lost in reception of the Soaps Of Tsaress SHA'HARINA A DOTYAVICH or perhaps have been recipient of late soaps in their delivery & would like to place a complain to the Human Resources Management, please fill form below: </h3>



    <Formik
      initialValues={{
        firstName: '',
        lastName: '',
        email: '',
      }}
      onSubmit={async (values) => {
        await new Promise((r) => setTimeout(r, 500));
        alert(JSON.stringify(values, null, 2));
      }}
    >
      <Form>
        <label htmlFor="firstName">First Name</label>
        <Field id="firstName" name="firstName" placeholder="Jane" />

        <label htmlFor="lastName">Last Name</label>
        <Field id="lastName" name="lastName" placeholder="Doe" />

        <label htmlFor="email">Email</label>
        <Field
          id="email"
          name="email"
          placeholder="jane@acme.com"
          type="email"
        />
        <button type="submit">Submit</button>
      </Form>
    </Formik>
  </div>
);

ReactDOM.render(<Basic />, document.getElementById('root'));
</script>

    <!--
      This HTML file is a template.
      If you open it directly in the browser, you will see an empty page.
      You can add webfonts, meta tags, or analytics to this file.
      The build step will place the bundled scripts into the <body> tag.
      To begin the development, run `npm start` or `yarn start`.
      To create a production bundle, use `npm run build` or `yarn build`.
    -->
  </body>
</html>


<script>
import React from 'react';
import ReactDOM from 'react-dom';
import { Formik, Field, Form } from 'formik';

const Basic = () => (
  <div class= "justify-content-center">
    <h1>CONTACTING</h1>
    <h2> VOLOSKYR, SVRYEIDA KURDRADISH</h2>
    <h3> <p>REGARDING, these soaps having been brewed which rather late the month of May, it's origins being from the Western Siberian Plains post abolition, having graced the bath halls of late TSARESS SHA'HARINA A. DOTYAVICH through the coldest months of these northern climes. In mourning, it's long awaited delivery accompanied by such cold & blustery winds alongside the folding of 1,000 paper cranes & tired hands. For a great many days the weather would never permit travel across the Pacific Tundras. </p>
      
      <p>Should you have been at all " put-off " by the delay in arrival time, please know the professional Bureau of Telekinetic Affairs has been informed. </p></h3>
     <h6><p>Please be aware that said soap samples in their laboratory preparation have been well freeze dried disregarding departure times. These processes have in no way changed due to International Standards of  Trading. These conditions have in no way changed due to International Standards of Storing.
       </p></h6>
       <h3> Have you been the recipient of these soaps? Have your soaps been lost in the mail? Should you have been lost in reception of the Soaps Of Tsaress SHA'HARINA A DOTYAVICH or perhaps have been recipient of late soaps in their delivery & would like to place a complain to the Human Resources Management, please fill form below: </h3>



    <Formik
      initialValues={{
        firstName: '',
        lastName: '',
        email: '',
      }}
      onSubmit={async (values) => {
        await new Promise((r) => setTimeout(r, 500));
        alert(JSON.stringify(values, null, 2));
      }}
    >
      <Form>
        <label htmlFor="firstName">First Name</label>
        <Field id="firstName" name="firstName" placeholder="Jane" />

        <label htmlFor="lastName">Last Name</label>
        <Field id="lastName" name="lastName" placeholder="Doe" />

        <label htmlFor="email">Email</label>
        <Field
          id="email"
          name="email"
          placeholder="jane@acme.com"
          type="email"
        />
        <button type="submit">Submit</button>
      </Form>
    </Formik>
  </div>
);

ReactDOM.render(<Basic />, document.getElementById('root'));
</script>

<div class="container">
  <form action="action_page.php">

    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="country">Country</label>
    <select id="country" name="country">
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">

  </form>
</div>
