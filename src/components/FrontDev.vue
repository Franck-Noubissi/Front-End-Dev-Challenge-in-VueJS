<template>
  <div class="container">
    <!-- Card Home-->
    <div class="card">
      <img class="opacity" src="../assets/images/acceuil.jpg" alt="acceuil" />
      <div class="card-details">
        <div class="title"><h1>Front-End</h1></div>
        <div class="subtitle"><h2>valtech_</h2></div>
        <div class="description">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
          voluptates placeat cum quaerat id hic.
        </div>
        <button>Explore more</button>
      </div>
    </div>

    <!-- First block-->
    <div class="first">
      <div class="card">
        <picture>
          <source media="(max-width: 768px)" srcset="../assets/images/venice1.jpg" />
          <img src="../assets/images/venice2.jpg" alt="" />
        </picture>
        <div class="card-details">
          <div class="title"><h1>Italy</h1></div>
          <div class="subtitle"><h2>Venice</h2></div>
          <div class="description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
            voluptates placeat.
          </div>
          <button>Explore more</button>
        </div>
      </div>

      <div class="card">
        <picture>
          <source media="(max-width: 768px)" srcset="../assets/images/berlin1.jpg" />
          <img src="../assets/images/berlin2.jpg" alt="" />
        </picture>
        <div class="card-details">
          <div class="title"><h1>Germany</h1></div>
          <div class="subtitle"><h2>Berlin</h2></div>
          <div class="description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
            voluptates placeat.
          </div>
          <button>Explore more</button>
        </div>
      </div>

      <div class="card">
        <picture>
          <source
            media="(max-width: 768px)"
            srcset="../assets/images/barcelona2.jpg"
          />
          <img src="../assets/images/barcelona.jpg" alt="" />
        </picture>
        <div class="card-details">
          <div class="title"><h1>Spain</h1></div>
          <div class="subtitle"><h2>Barcelona</h2></div>
          <div class="description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
            voluptates placeat.
          </div>
          <button>Explore more</button>
        </div>
      </div>
    </div>

    <!-- Second block-->
    <div class="second">
      <div class="card">
        <picture>
          <source media="(max-width : 765px)" srcset="../assets/images/Paris1.jpg" />
          <img src="../assets/images/paris4.jpg" alt="" />
        </picture>
        <div class="card-details">
          <div class="title"><h1>France</h1></div>
          <div class="subtitle"><h2>Paris</h2></div>
          <div class="description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
            voluptates placeat.
          </div>
          <button>Explore more</button>
        </div>
      </div>

      <div class="card">
        <picture>
          <source media="(max-width: 768px)" srcset="../assets/images/amsterdam.jpg" />
          <img src="../assets/images/amsterdam1.jpg" alt="" />
        </picture>
        <div class="card-details">
          <div class="title"><h1>Netherlands</h1></div>
          <div class="subtitle"><h2>Amsterdam</h2></div>
          <div class="description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
            voluptates placeat.
          </div>
          <button>Explore more</button>
        </div>
      </div>

      <div class="card">
        <picture>
          <source media="(max-width: 768px)" srcset="../assets/images/london1.jpg" />  
          <img src="../assets/images/london.jpg" alt="" />
        </picture>
        <div class="card-details">
          <div class="title"><h1>United Kingdom</h1></div>
          <div class="subtitle"><h2>London</h2></div>
          <div class="description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
            voluptates placeat.
          </div>
          <button>Explore more</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FrontDev",
};
</script>
