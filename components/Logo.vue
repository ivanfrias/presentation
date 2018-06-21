<template>
  <div>
      <div class="blue-grey lighten-5">
          <div class="blue-grey--text main_text">
            //work-in-progress
          </div>
      </div>
      <div class="menu">
          <div>
            <span>
              <nuxt-link to="/">Home</nuxt-link> |
              <nuxt-link to="/projects">Projects</nuxt-link> |
              <nuxt-link to="/contacts">Contacts</nuxt-link>
            </span>
          </div>
      </div>
    </div>
</template>

<style>

.main_text {
  font-size: 30px;
  margin-left: 10px;
}

.secondary_text {
  border-top: 1px solid #b0bec5;
  font-size: 14px;
}

.with_some_margin {
  margin-left: 10px;
}

.menu {
  margin-top: 5px;
  width: 100%;
}

</style>
