<template>
  <div id="experience">
   <h1>Education / Experience<span id="hi_">👋</span></h1>
   <div class="c_content">
      <div class="c_experience">
         <div class="c_date">
            2012 - 2016
         </div>
         <div class="c_title">
            Tay Nguyen University
         </div>
         <div class="c_subtitle">
            Information technology
         </div>
      </div>
      <div class="c_experience">
         <div class="c_date">
            2017 - Present
         </div>
         <div class="c_title">
            Working remotely
         </div>
         <div class="c_subtitle">
            Full Stack developer    
         </div>
      </div>
   </div>
</div>
</template>

<script>
export default {
  name: "Experience"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    $blue: #2257ea;
    #experience {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        font-size: 1.4rem;
        padding: 1rem 2rem;
        min-height: 60vh;
        p {
            text-align: center;
            a {
                text-decoration: none;
                color: $blue;
            }
        }
        h1 {
            text-align: center;
        }
        .c_content {
            display: flex;
            justify-content: space-evenly;
            margin-top: 60px;
            flex-wrap: wrap;
            width: 100%;
        }
        .c_experience {
            min-width: 300px;
            display: block;
            position: relative;
            margin-bottom: 40px;
            padding: 25px;
            -webkit-box-shadow: 0 8px 45px rgba(0, 0, 0, 0.15);
            box-shadow: 0 8px 45px rgba(0, 0, 0, 0.15);
            .c_title {
                font-weight: 700;
                display: block;
                font-size: 16px;
            }
            .c_subtitle {
                font-size: 15px;
            }
            .c_date {
                font-size: 14px;
                position: absolute;
                top: -25px;
                right: 45px;
                background: #4c33fb;
                padding: 10px 25px;
                font-weight: 600;
                color: #fff;
                -webkit-box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.2);
                box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.2);
                -webkit-transition: opacity 0.25s, transform 0.25s;
                transition: opacity 0.25s, transform 0.25s;
                margin-bottom: 0;
            }
        }
    }
    #hi_ {
        animation: shake 0.5s infinite ease-in-out alternate;
        display: inline-block;
        z-index: 0;
    }
    @media only screen and (max-width: 500px) {
        #experience {
            padding: 1rem;
        }
    }
    @keyframes shake {
        from {
            transform: rotate(0deg);
        }
        to {
            transform: rotate(20deg);
        }
    }

</style>
