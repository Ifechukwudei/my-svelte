<form class="form" id="contact-form">
  <input type="hidden" name="contact_number">
  <label for="name">Name:</label><br />
  <input class="input" type="text" id="name" name="name" /><br />
  <label for="email">Email:</label><br />
  <input class="input" type="email" id="email" name="email" /><br />
  <label for="message">Message:</label><br />
  <textarea
    class="input"
    id="message"
    name="message"
    rows="7"
    cols="30"
  ></textarea>
  <br /><br />
  <input class="submit" type="submit" value="Send" />
</form>

<style>
            
  /* Add some basic styling to the form */
  form.form {
  background-color: black;
  width: 50%;
  margin: 0 auto;
  border: 1px solid rgb(0, 132, 255);
  padding: 20px;
  box-sizing: border-box;
  color: #ccc;

  }

  /* Style the input fields */
  form.form input.input,
  form.form textarea.input {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
  border: 1px solid #ccc;
  border-radius: 4px;
  }

  /* Style the submit button */
  form.form input[type='submit'].submit {
  /* width: calc(100% /2); */
  background-color: rgb(0, 132, 255);
  color: white;
  padding: 10px 40px;
  margin: 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  }

  /* Add a hover effect to the submit button */
  form.form input[type='submit'].submit:hover {
  background-color: rgb(35, 66, 243);
  }
</style>