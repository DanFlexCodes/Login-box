//html code
<!DOCTYPE html>

<html lang="en">

<head>
  <link rel="stylesheet" href="styles.css">
  <title>DanFlex</title>
</head>

<body>
  <section>
     
    <div class="form-box">
      <div class="form-value">
        <form action="">
          <h2>LOGIN</h2>
          <div class="inputbox">
            <input type="name" required>
            <label for="">Username</label>
          </div>
          <div class="inputbox">
            <input type="password" required>
            <label for="">Password</label>
          </div>
          <div class="forget">
            <label>
              <p>Forget <a href="#">Password</a>
            </label></p>

          </div>
          <button>Log in</button>
          <div class="register">
            <p>Don't have a account <a href="#">Register</a></p>
          </div>
        </form>
      </div>
    </div>
  </section>
</body>

</html>
//css code
*{
   margin: 0;
   padding: 0;
}
section {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  width: 100%;
  background: url('1.jpeg');
  background-position: center;
  background-size: cover;
}

.form-box {
  position: relative;
  width: 400px;
  height: 450px;
  background: transparent;
  border: 2px solid rgba(255, 255, 255, 0.5);
  border-radius: 20px;
  backdrop-filter: blur(5px);
  display: flex;
  justify-content: center;
  align-items: center
}

h2 {
  font-size: 2em;
  color: #ffd700;
  text-align: center;
}

.inputbox {
  position: relative;
  margin: 30px 0;
  width: 310px;
  border-bottom: 2px solid #fff;
}

.inputbox label {
  position: absolute;
  top: 50%;
  left: 5px;
  transform: translateY(-50%);
  color: #ffd700;
  font-size: 1em;
  transition: .5s;
}

input:focus~label,
input:valid~label {
  top: -5px;
}

.inputbox input {
  width: 100%;
  height: 50px;
  background: transparent;
  border: none;
  outline: none;
  font-size: 1em;
  padding: 0 35px 0 5px;
  color: #fff;
}

.inputbox ion-icon {
  position: absolute;
  right: 8px;
  color: #fff;
  font-size: 1.2em;
  top: 20px;
}

.forget {
  margin: -15px 0 15px;
  font-size: .9em;
  color: #ffd700;
  display: flex;
  justify-content: center;
}

.forget label input {
  margin-right: 3px;

}

.forget label a {
  color: #ffd700;
  text-decoration: none;
  font-weight: 600
}

.forget label a:hover {
  text-decoration: underline;
}

button {
  width: 100%;
  height: 40px;
  border-radius: 40px;
  background: #fff;
  border: none;
  outline: none;
  cursor: pointer;
  font-size: 1em;
  font-weight: 600;
}

.register {
  font-size: .9em;
  color: #ffd700;
  text-align: center;
  margin: 25px 0 10px;
}

.register p a {
  text-decoration: none;
  color: #fff;
  font-weight: 600;
}

.register p a:hover {
  text-decoration: underline;
}