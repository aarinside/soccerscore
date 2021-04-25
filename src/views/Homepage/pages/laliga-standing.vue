<template>
  <div class="background">
    <div class="container">
      <div class="image">
        <img
          src="../../../assets/logo-stan.jpg"
          alt=""
          class="image-position"
        />
        <h1>LaLiga</h1>
      </div>
    </div>
    <div class="tab-bar">
      <ul class="nav">
        <li class="nav-item mx-sm-5">
          <a class="nav-link active" href="homepage">home</a>
        </li>
        <li class="nav-item mx-sm-5">
          <a class="nav-link " href="">standing</a>
        </li>
        <li class="nav-item mx-sm-5">
          <a class="nav-link" href="premeir-schedule">schedule</a>
        </li>
      </ul>
    </div>
    <div class="table-data">
      <table class="table table-striped">
        <thead class="thead-dark">
          <tr>
            <th scope="col">Pos</th>
            <th scope="col">Club</th>
            <th scope="col">Pl</th>
            <th scope="col">GD</th>
            <th scope="col">Pts</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>Manchester City</td>
            <td>32</td>
            <td>+60</td>
            <td>76</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>Manchester United</td>
            <td>31</td>
            <td>+45</td>
            <td>68</td>
          </tr>
          <tr>
            <th scope="row">3</th>
            <td>Leicester</td>
            <td>31</td>
            <td>+30</td>
            <td>58</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.table {
  font-size: 20px;
  font-family: "B612", sans-serif;
}
a {
  font-size: 25px;
  color: black;
}
.tab-bar {
  display: flex;
  align-items: center;
  justify-content: center;
  color: black;
  padding-left: 10px;
  padding-right: 10px;
  margin-top: 10px;
}
.container {
  width: 90vw;
  margin: 0 auto;
}
.background {
  width: 100%;
  height: 120px;
  background-color: #fac400;
}
.image {
  display: flex;
  align-items: center;
  font-family: Regular, sans-serif, Georgia;
}
.image-position {
  background-color: white;
  padding: 5px 5px;
  width: 100px;
  height: 100px;
  background: white;
  -moz-border-radius: 70px;
  -webkit-border-radius: 70px;
  border-radius: 70px;
  margin-top: 10px;
}

h1 {
  margin-left: 30px;
  color: aliceblue;
  margin-top: 15px;
}
</style>
