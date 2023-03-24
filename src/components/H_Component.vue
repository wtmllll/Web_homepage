<template>

  <section>
      
    
      
        <div class="containers">
        <img class="img" src="../assets/Logo2.png" alt="zeitplan Logo">
        <p class="zeitplan">ZEITPLAN</p>
        <table>
          
          <td><a href="#home" class="active">Home</a></td>
          <td><a href="#Fitur">Fitur-Fitur</a></td>
          <td><a href="#Harga">Harga</a></td>
          <td><a href="#Testimoni">Testimoni</a></td>
          
          <td><button class="b_Download">Download<span style='font-size:20px;'>&#8594;</span>
            </button></td>
      </table>
      </div>

      <div class="container2">
        <p class="Sebuah">Sebuah cara mudah mengatur jadwal kuliah kamu</p>
        <p class="Datang">Datang kuliah terlambat karena ketiduran itu tidak masalah; 
          datang kuliah karena lupa jadwal itu sangatlah tidak keren. Aplikasi ini adalah 
          sahabat kamu sekarang, brodie~</p>
        <button class="b_LearnMore">Learn More</button>
        <button class="b_PlayDemo">Play Demo</button>
        <div class="slideContent">
            <div class="row">
              <div class="column">
                <img class="star" src="../assets/star.png" alt="Star Yellow">
              </div>
              <div class="column">
                <img class="star" src="../assets/star2.png" alt="Star Gray">
              </div>
              <div class="column">
                <img class="star" src="../assets/star2.png" alt="Star Gray">
              </div>
              <div class="column">
                <img class="star" src="../assets/star2.png" alt="Star Gray">
              </div>
              <div class="column">
                <img class="star" src="../assets/star2.png" alt="Star Gray">
              </div>
            </div>

          <div>
            <p class="Aplikasi">“Aplikasi sialan, ini gw jadi kagak bisa alesan lagi buat bolos 
              kelas Pak Sanusi yang galak itu! Tapi aku sekarang jadi rajin kuliah, terima kasih garena!”</p>
            <img class="profSlidePic" src="../assets/profileSlidePic.png" alt="Profile Slide Picture">
            <p class="P-Star7">P-Star 7</p>
            <p class="Mahasiswa">Mahasiswa Boating School Ny. Puff</p>
            <button class="b_carousel">
                <img class="next" src="../assets/next.png" alt="next">
            </button>
            <button class="b_carousel2" style="transform: matrix(1, 0, 0, 1, 0, 0);right:50px;">
                <img class="next2" src="../assets/next.png" alt="next">
            </button>
          </div>

          </div>

          
      </div>
    
    
    
    

  </section>
</template>

<script>
export default {
    name: 'H_ComponentVue'
}
</script>

<style>
   body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 0px;
    height: 1035px;
    background: linear-gradient(180deg, rgba(255, 244, 242, 0.4) 0%, #FFF0EE 100%);

    }

    .img {
      width: 38px;
      height: 38px;
      left: 0px;
      top: 50px;
      margin-left: 50px;
      margin-top: 33px;
      float: left;
    }

    .row {
      display: flex;
    }

    .column {
      padding: 3px;
    }

    .star {
      height: 20px;
      width: 20px;
      left: 10%;
      top: 30px;
    }

    p.zeitplan {
      width: 87px;
      height: 27px;
      left: 52px;
      top: 6px;
      float:left;
      font-family: 'Poppins';
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 27px;
      margin-left: 15px;
      margin-top: 40px;

      /* identical to box height */

      letter-spacing: 0.05em;
    }

    p.Sebuah {
      width: 501px;
      height: 150px;
      float: left;
      font-family: 'Patua One';
      font-style: normal;
      font-weight: 350;
      font-size: 48px;
      text-align: left;
      line-height: 60px;
      padding: auto;
      /* or 125% */


      /* Dark */

      color: #0E144A;
    }

    p.Datang {
      font-family: 'Source Sans Pro';
      font-style: normal;
      font-weight: 400;
      font-size: 18px;
      line-height: 34px;
      color: #6F6F6F;
      padding: auto;
      text-align: Left;
      vertical-align: text-bottom;

    }
    
    p.Aplikasi {
      font-family: 'Poppins';
      font-style: normal;
      font-weight: 400;
      font-size: 14px;
      line-height: 28px;
      text-align: left;
      color: #0E144A;

    }

    p.P-Star7 {
      position: relative;
      font-family: 'Poppins';
      font-size: 16px;
      font-weight: 600;
      line-height: 24px;
      letter-spacing: 0em;
      border: 20px;
      left: 20px;
      float: left;
      width: 65px;
      height: 20px;
      }

    p.Mahasiswa {
      position: relative;
      font-weight: 600;
      font-family: 'Poppins';
      font-style: normal;
      font-weight: 500;
      font-size: 12px;
      line-height: 18px;
      color: rgba(14, 20, 74, 0.6);
      float: left;
      margin-top: 40px;
      width: 211px;
      text-align: Left;
      vertical-align: text-bottom;
      left: initial;
    }

    .profSlidePic {
      width: 55px;
      height: 55px;
      float: left;
      padding-top: 5px;

    }

.containers {
    
    list-style-type: none;
    /*margin-left: 120px;*/
    margin-right: 120px;
    margin-top: 50px;
    overflow: hidden;
    background-color: #FFFF;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 30px, 40px, 30px, 40px;
    margin-left: 8%;
    width: 1168px;
    height: 100px;
    box-shadow: 0px 30px 60px rgba(0, 0, 0, 0.05);
    border-radius: 6px;

    /* Inside auto layout */

    flex: none;
    order: 0;
    flex-grow: 0;

}

.container2 {
  list-style-type: none;
    margin-left: 120px;
    margin-right: 120px;
    margin-top: 50px;
    overflow: hidden;
    flex-direction: column;

    padding: 30px, 40px, 30px, 40px;
    margin-left: 8%;
    width: 501px;
    height: 720px;
}

.slideContent {
    flex-direction: column;
    align-items: flex-start;
    padding: 30px;
    gap: 20px;

    position: absolute;
    width: 400px;
    height: 200px;
    margin-top: 100px;
    left: 8%;
    

    background: #FFFFFF;
    /* Shadow Primary */

    box-shadow: 0px 30px 60px 0px #FE5E441A;
    border-radius: 6px;
    }

  table {
    float: right;
    margin-right: 40px;
    font-family: 'Source Sans Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 20px;

  }

td {
  float: left;
  padding: 30px 0;
  background-color: #FFFF;
  margin-left: 20px;
}

td a {
  display: inline-block;
  color: rgba(0, 0, 0, 0.5);
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

td a:hover {

  color: #af928e;
}

.active {
  color: #FE5E44;
}

.b_Download {
    width: 145px;
    height: 40px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 10px 20px;
    gap: 15px;
    background: #FE5E44;
    box-shadow: 0px 20px 30px rgba(255, 86, 58, 0.15);
    border-radius: 5px;
    border-color: #FE5E44;
;
    border-block-color: #FE5E44;
    flex: none;
    order: 4;
    flex-grow: 0;
    font-family: 'Source Sans Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;

    color: #FFFF;
    }

    .b_LearnMore {
      flex-direction: row;
      justify-content: center;
      align-items: center;
      gap: 10px;

      width: 177px;
      height: 50px;
      margin-top: 30px;
      margin-right: 20px;

      /* Primary */
      border-color: #FE5E44;
      background: #FE5E44;
      box-shadow: 0px 20px 30px 0px #FF563A26;
      border-radius: 5px;
      color: #FFFF;

      font-family: 'Source Sans Pro';
      font-style: normal;
      font-weight: 500;
      font-size: 16px;
      line-height: 20px;
    }

    .b_PlayDemo {
      flex-direction: row;
      justify-content: center;
      align-items: center;
      padding: 15px 50px;
      gap: 10px;
      width: 174px;
      height: 50px;
      float : right;
      margin-top: 30px;
      margin-right: 130px;
      padding: 0;
      border-color: #FE5E44;
      background: rgba(254, 94, 68, 0.1);;
      border-radius: 5px;
      
      border-width: 1px;

      /*background: rgba(254, 94, 68, 0.1);
      border: 1px solid #FE5E4433;
      background: linear-gradient(0deg, rgba(254, 94, 68, 0.2), rgba(254, 94, 68, 0.2)),
      linear-gradient(0deg, rgba(254, 94, 68, 0.1), rgba(254, 94, 68, 0.1));*/
      color: #FE5E44;
      /* Pirmary Light */
      border-radius: 5px;

      font-family: 'Source Sans Pro';
      font-style: normal;
      font-weight: 600;
      font-size: 16px;
      line-height: 20px;
    }

    .b_carousel {
      position: relative;
      width: 33px;
      height: 33px;
      border-radius: 50px;
      /* Pirmary Light */
      top: 33px;
      display: flex;
      transform: matrix(-1, 0, 0, 1, 0, 0);
      background: #FE5E4433;
      border: 1px solid #FE5E4433;
      flex-direction: row;
      justify-content: center;
      align-items: center;
    }

    .next {
      height: 28px;
      width: 20px;
      border-radius: 0px;
      border-width: 1px;

    }

    .b_carousel2 {
      position: relative;
      width: 33px;
      height: 33px;
      border-radius: 50px;
      /* Pirmary Light */
      left: 40px;
      display: flex;
      transform: matrix(1, 0, 0, 1, 0, 0);
      background: #FE5E4433;
      border: 1px solid #FE5E4433;
      flex-direction: row;
      justify-content: center;
      align-items: center;
    }

    .next2 {
      height: 28px;
      width: 20px;
      border-radius: 0px;
      border-width: 1px;

    }
</style>