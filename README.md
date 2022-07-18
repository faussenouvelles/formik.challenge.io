# formik.challenge.io
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
