<script>
    import Header from "$lib/components/Header.svelte";
    import Hero from "$lib/components/Hero.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<Header />

<Hero />

<!-- TO BE REMOVED-->
<section class="home-category">

   <h1 class="title">shop by category</h1>

   <div class="box-container">

      <div class="box">
         <img src="images/cat-1.png" alt="poulet">
         <h3>poulet de chair</h3>
         <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Exercitationem, quaerat.</p>
         <a href="category.php?category=poulet" class="btn">fruits</a>
      </div>

      <div class="box">
         <img src="images/cat-2.png" alt="porc">
         <h3>porc</h3>
         <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Exercitationem, quaerat.</p>
         <a href="category.php?category=porc" class="btn">porc</a>
      </div>

      <div class="box">
         <img src="images/cat-3.png" alt="canard">
         <h3>canard</h3>
         <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Exercitationem, quaerat.</p>
         <a href="category.php?category=canard" class="btn">canard</a>
      </div>

      <div class="box">
         <img src="images/cat-4.png" alt="pigeon">
         <h3>pigeon</h3>
         <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Exercitationem, quaerat.</p>
         <a href="category.php?category=pigeaon" class="btn">pigeon</a>
      </div>

       <div class="box">
           <img src="images/cat-5.png" alt="caille">
           <h3>caille</h3>
           <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Exercitationem, quaerat.</p>
           <a href="category.php?category=caille" class="btn">caille</a>
       </div>

   </div>

</section>

<section class="products">

   <h1 class="title">latest products</h1>

   <div class="box-container">

      <form action="" class="box" method="POST">
      <div class="price">$<span>13</span></div>
      <a href="view_page.php?pid=25" class="fas fa-eye"></a>
      <img src="uploaded_img/Capture d’écran 2023-06-26 181851.jpg" alt="">
      <div class="name">BB02</div>
      <input type="hidden" name="pid" value="25">
      <input type="hidden" name="p_name" value="BB02">
      <input type="hidden" name="p_price" value="13">
      <input type="hidden" name="p_image" value="Capture d’écran 2023-06-26 181851.jpg">

            <input type="number" min="1" max="4" value="1" name="p_qty" class="qty">

      <input type="text" value="4 left" class="btn" name="qty_left" readonly="">

            <input type="submit" value="add to cart" name="add_to_cart" class="btn">

   </form>

   </div>

</section>
<!-- TO BE REMOVED-->

<Footer />