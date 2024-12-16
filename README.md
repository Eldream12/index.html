<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Axia Registration Form</title>
    <link rel="stylesheet" href="/style.css" />
  </head>
  <body>
    <img src="/images/login-form-8.jpg" alt="form" width="5%" />

    <header>
      <h1>Sign Up</h1>
      <h2>Axia Form</h2>
    </header>

    <!-- form area -->
    <main>
      <section>
        <form class="" action="" method="">
          <div class="textarea">
            <label for="firstname">First Name</label>
            <br />
            <input type="text" name="Firstname" />
          </div>

          <div class="textarea">
            <label for="lastname">Last Name</label>
            <br />
            <input type="text" name="lastname" />
          </div>

          <div class="textarea">
            <label for="email">Email</label>
            <br />
            <input type="email" name="email" />
          </div>

          <div>
            <label for="gender">Gender</label>
            <br />

            <!-- <option value="">Male</option>
            <input type="radio" name="gender" /> -->
            <label for="male">Male</label>
            <input type="radio" id="male" name="gender" value="Male" />

            <!-- <option value="">Female</option>
            <input type="radio" name="gender" /> -->
            <label for="female">Female</label>
            <input type="radio" id="female" name="gender" value="Female" />

            <!-- <option value="">others</option>
            <input type="radio" name="gender" /> -->
            <label for="others">Others</label>
            <input type="radio" id="others" name="gender" value="Others" />
          </div>

          <div class="textarea">
            <label for="password">Password</label>
            <br />
            <input type="password" name="password" />
          </div>

          <div class="textarea">
            <label for="confirmpassword">Confirm Password</label>
            <br />
            <input type="password" name="password" />
          </div>

          <div class="textarea">
            <label for="educationallevel">Educational Level</label>
            <br />
            <select name="educationallevel" />
            <option value>SSCE</option>
            <option value>BSc</option>
            <option value>MSc</option>
            <option value>PhD</option>
          </div>

          <div class="textarea">
            <label for="experiencelevel">Experience Level</label>
            <br />
            <select name="experiencelevel" />
            <option value>0-2 Years</option>
            <option value>3-5 Years</option>
            <option value>6-10 Years</option>
            <option value>Above 10 Years</option>
          </div>

          <div>
            <label for="text">Tell us about you</label>
            <br />
            <textarea
              name="text"
              placeholder="typehere"
              maxlength="20"
              minlength="10"
            ></textarea>
          </div>

          <!-- <input type="create account" name="" /> -->
          <button>Create account</button>
        </form>
      </section>
    </main>
  </body>
</html> 
)

