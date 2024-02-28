<template lang="">
  <div>
    <div class="container-2">
      <footer class="footer-div">
        <div class="text-content">
          <p class="text-div">© Jobkhuzi.com</p>
        </div>
        <div class="icon-content">
          <a class="icon-icon" href="https://www.facebook.com/fractalslab">
            <button class="button-1">f</button>
          </a>
          <a
            class="icon-icon fs-3 fw-bold text-white text-decoration-none"
            href="https://www.linkedin.com/company/fractalslab/"
          >
            <button class=" button-2">in</button>
          </a>
        </div>
      </footer>
    </div>
  </div>
</template>
<script>
export default {
  name: 'FooterComponent',

}
</script>
<style>
.button-1 {
  margin-left: 10px;
  font-size: 24px;
  color: white;
  font-weight: bolder;
  height: 40px;
  width: 40px;
  border-radius: 50%;
  border: none;
  background-color: rgb(57, 91, 154);
  box-shadow: 0 0px 20px 0 rgb(57, 91, 154);
  transition: all 0.4s;
}
.button-2 {
  margin-left: 10px;
  font-size: 24px;
  color: white;
  font-weight: bolder;
  height: 40px;
  width: 40px;
  border-radius: 50%;
  border: none;
  background-color: rgb(0, 172, 237);
  box-shadow: 0 0px 20px 0 rgb(0, 172, 237);
  transition: all 0.4s;
}
.button-1:hover {
  width: 90px;
  border-radius: 50px;
}
.button-2:hover {
  width: 90px;
  border-radius: 50px;
}

.footer-div {
  position: fixed;
  bottom: 0;
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  padding-left: 20px;
  padding-right: 20px;
  border-top: 2px solid rgb(126, 126, 126);
}
.text-content {
  padding: 1px;
}
.text-div {
  align-items: center;
  opacity: 0.5;
}
.icon-content {
  display: flex;
  gap: 20px;
  padding: 10px;
  align-items: center;
}
.icon-icon {
  font-size: 16px;
  font-weight: 800;
  color: white;
  text-decoration: none;
}

</style>
