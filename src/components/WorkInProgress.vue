<template>  
    <div class="work_in_progress">
        <img class="image" :src="require('@/assets/images/restaurant_logo_black.png')"/>
        <span>Próxima apertura otoño 2022</span>
        <span>C/ Juanín de Mieres · 33600 · Mieres · Asturias</span>
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
    height: 30%;
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
}

span {
    font-size:0.875rem;
    color: white;
    margin-bottom:0.5rem;
    text-align: center;
}

    @media only screen and (min-width: 768px) {
    .work_in_progress {
    width: 50%;
    height: 50%;
    }

        span {
        font-size:1rem;
    }
}

</style>


