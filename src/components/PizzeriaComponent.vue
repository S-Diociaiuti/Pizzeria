<template>
  <div class="pizzeria">
    <div class="header">
      <img src="../assets/logo-pizza.jpg" alt="">
    </div>
    <div class="banner">
      <img src="../assets/banner-pizza.jpg" alt="">
    </div>
    <div class="title">
      <h1>Pizza Park - The Best Italian Pizza!</h1>
      <h2>Order what you want, leave the rest to us!</h2>
    </div>
    <div class="forms">
      <div class="lista-pizze">
        <ul>
          <li>
            <img src="../assets/pizza_margherita.png" alt="">
            <div class="pizza">
              <span class="pizza-name"><b>Margherita</b></span>
              <h5><span class="pizza-ingredients">(Tomato Sauce, Mozzarella Cheese, Basil)</span></h5>
              <span class="price">5€</span>
            </div>
          </li>
          <li>
            <img src="../assets/wurstel.jpg" alt="">
            <div class="pizza">
              <span class="pizza-name"><b>Wurstel</b></span>
              <h5><span class="pizza-ingredients">(Tomato Sauce, Mozzarella Cheese, Wurstel, French Fries)</span></h5>
              <span class="price">6€</span>
            </div>
          </li>
          <li>
            <img src="../assets/pepperoni.png" alt="">
            <div class="pizza">
              <span class="pizza-name"><b>Pepperoni Pizza</b></span>
              <h5><span class="pizza-ingredients">(Tomato Sauce, Mozzarella Cheese, Pepperoni)</span></h5>
              <span class="price">6.50€</span>
            </div>
          </li>
          <li>
            <img src="../assets/patate-salsiccia.jpg" alt="">
            <div class="pizza">
              <span class="pizza-name"><b>Potatoes & Sausage</b></span>
              <h5><span class="pizza-ingredients">(Potatoes, Mozzarella Cheese, Sausages)</span></h5>
              <span class="price">7€</span>
            </div>
          </li>
          <li>
            <img src="../assets/marinara.jpg" alt="">
            <div class="pizza">
              <span class="pizza-name"><b>Marinara</b></span>
              <h5><span class="pizza-ingredients">(Tomato Sauce, Origan, Olive Oil, Garlic)</span></h5>
              <span class="price">5€</span>
            </div>
          </li>
          <li>
            <img src="../assets/bismark.jpg" alt="">
            <div class="pizza">
              <span class="pizza-name"><b>Bismark</b></span>
              <h5><span class="pizza-ingredients">(Tomato Sauce, Mozzarella Cheese, Prosciutto Crudo, Egg)</span></h5>
              <span class="price">6.50€</span>
            </div>
          </li>
        </ul>
      </div>
      <div class="form">
          <form>
            <div class="form-content">
              <label for="fname"><i class="bi bi-person"></i>First name</label><br>
              <input type="text" id="fname" name="fname">
            </div>
            <div class="form-content">
              <label for="lname"><i class="bi bi-person"></i>Last name</label><br>
              <input type="text" id="lname" name="lname">
            </div>
            <div class="form-content">
              <label for="email"><i class="bi bi-envelope"></i>Email</label><br>
              <input type="email" id="email" name="email">
            </div>
            <div class="form-content">
              <label for="tel"><i class="bi bi-phone"></i>Cell phone</label><br>
              <input type="tel" id="tel" name="tel">
            </div>
            <div class="form-content">
              <label for="address"><i class="bi bi-building"></i>Address</label><br>
              <input type="text" id="address" name="address">
            </div>
            <div class="form-content">
              <label for="order"><i class="bi bi-clipboard"></i>Order</label><br>
              <textarea id="order" name="order" placeholder="Write here your order"></textarea><br>
            </div>
            <input type="submit" value="Order now">
          </form>
        </div>
    </div>
    <footer>
      <h2>Pizza Park</h2>
      <div class="follow-us">
        <i class="bi bi-instagram"><a href="">Follow Us on Instagram!</a></i>
        <i class="bi bi-facebook"><a href="">Follow Us on Facebook!</a></i>
        <i class="bi bi-envelope-at">PizzaPark@business.com</i>
        <i class="bi bi-whatsapp">3341456598</i>
      </div>
    </footer>
  </div>  
</template>

<script>
import '../assets/styles/components/pizzeria.scss'
export default {
  name: 'PizzeriaComponent',
  props: {
  }
}
</script>

