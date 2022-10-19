<template>  
    <div class="work_in_progress">
        <img class="image" :src="require('@/assets/images/restaurant_logo_black.png')"/>
        <span>Estamos cocinando nuestra web.</span>
        <span>Mientras tanto puedes realizar tu reserva </span>
        <span>por teléfono </span>
        <span><a href="tel:984-285-024">984 285 024</a></span>
        <span>o por correo electrónico</span>
        <span><a href="mailto:reservas@bobelarestaurante.es">reservas@bobelarestaurante.es</a></span>
        <span>¡Te esperamos!</span>
        <div class="social_media">
            <a href="https://www.instagram.com/bobelarestaurante/"><img class="social_media_logo" :src="require('@/assets/icons/instagram_icon.svg')"/></a>
            <a href="https://www.facebook.com/Bobela-Restaurante-105115832344696"><img class="social_media_logo" :src="require('@/assets/icons/facebook_icon.svg')"/></a>
        </div>
    </div>
</template>

<script>

export default {
  name: 'WorkInProgress',
}
</script>

<style scoped>
.work_in_progress {
    width: 100%;
    height: 45%;
    background-color: #CF3339;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 3rem 2rem;
    box-shadow: 0 10px 20px rgba(207,51,57, 0.3), 0 20px 30px rgba(207,51,57, 0.3);
}

.image {
    width: 50%;
    height:50%;
    margin-bottom:1em;
    animation: fadeIn 0.8s ease-in forwards;
    /* animation-delay:0.8s; */
    opacity: 0;
}

span {
    font-size:0.875rem;
    color: #fff;
    margin-bottom:0.5rem;
    text-align: center;
    animation: fadeIn 0.8s ease-in forwards;
    animation-delay:0.8s;
    opacity:0;
}

.social_media {
    display: flex;
    margin-top: 1.5rem;
    animation: fadeIn 0.8s ease-in forwards;
    animation-delay:1.6s;
    opacity:0;
}

.social_media_logo {
    padding:0.5rem;
}

a {
    color: #fff;
}


    @media only screen and (min-width: 768px) {
    .work_in_progress {
    width: 50%;
    height: 50%;
    }

        span {
        font-size:1rem;
    }

    .social_media {
        display: flex;
        margin-top: 1.5rem;
        width: auto;
    }

    .social_media_logo {
        width: 1.872rem;
        height: 1.872rem;
        padding:0.5rem;
    }
}

  @keyframes fadeIn {
        from {
            opacity: 0;
        }

        to {
            opacity: 1;
        }
    }

</style>


