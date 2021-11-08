<template>
  <b-container fluid>
    <b-row>
      <b-col>
        <div class="logo">
          <img src="../assets/miblogo.png" alt="" />
        </div>
      </b-col>
    </b-row>

    <b-row>
      <b-col>
        <div class="title">
          <h1>We Build Community and Great Apps</h1>
          <div class="isiTitle">
            <span
              >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Qui
              laborum quo ipsa nemo distinctio blanditiis aliquam nostrum
              laboriosam explicabo. Voluptatibus, perspiciatis aliquid! Nulla,
              alias quisquam ipsam dignissimos error odio voluptatem nostrum
              deleniti impedit itaque culpa aperiam laudantium natus assumenda!
              Exercitationem laborum natus, ipsam eius sunt fugit totam nemo
              sapiente repudiandae.</span
            >
          </div>
        </div>
      </b-col>
    </b-row>

    <b-row class="content1">
      <b-col>
        <div class="logo2">
          <img src="../assets/hnb.svg" alt="" />
          <h1>Duski Software House</h1>
        </div>
      </b-col>
      <b-col>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat maiores
        ipsum doloremque et possimus, delectus tenetur magnam, voluptates
        temporibus pariatur officiis provident asperiores. Ullam id magnam
        facere rerum tempore consequuntur.
      </b-col>
    </b-row>

    <b-row class="content2">
      <b-col>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat maiores
        ipsum doloremque et possimus, delectus tenetur magnam, voluptates
        temporibus pariatur officiis provident asperiores. Ullam id magnam
        facere rerum tempore consequuntur.
      </b-col>
      <b-col>
        <div class="logo3">
          <img src="../assets/fosanlogo.png" alt="" />
          <h1>Fosan Programming Academy</h1>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>

.title {
  text-align: center;
  align-items: center;
  justify-content: center;
  padding: 25px;
  h1 {
    font-size: 25px;
  }

  .isiTitle {
    align-items: center;
    width: 50%;
    justify-content: center;
    transform: translateX(50%);
  }
}

.logo {
  padding: 50px;
  img {
    width: 300px;
  }
}

.content1 {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
  padding: 24px;
  padding-top: 100px;
  .logo2 {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    transform: translateX(-20%);
  }
  img {
    display: flex;
    align-items: flex-end;
    width: 250px;
  }
  h1 {
    font-size: 25px;
  }
}

.content2 {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 24px;
  padding-top: 100px;
  .logo3 {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    transform: translateX(20%);
  }
  img {
    display: flex;
    align-items: flex-end;
    width: 250px;
  }
  h1 {
    font-size: 25px;
  }
}
</style>