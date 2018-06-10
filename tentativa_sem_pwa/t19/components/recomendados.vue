<template>
    <div class="background">
        <homepage-header></homepage-header>
        <div class="date">
                Sábado 9 de junio:
        </div>
        <div class="boxed">
            <div class="hora">
                10:00am
            </div> 
            <img :src="require('@/assets/ime.png')"/>
            <div class="title">           
                Aula de Aprendizado de Máquina
            </div> 
            <div class="descripcao">
                Prof: Nina </br>
                Sala: s. 144       
            </div> 
            <div class="tags">
                #aula
            </div> 
        </div>
        <div class="boxed">
            <div class="hora">
                6:00pm
            </div> 
            <img :src="require('@/assets/junime.png')"/>
            <div class="title">           
                JunIME
            </div> 
            <div class="descripcao">
                É mais uma JUNIME chegando nessa quadrilha demais de boa! E como sempre, teremos aquelas famosas delícias para esquentar esse arraiar sô! Vai ter:        
            </div> 
            <div class="tags">
                #tecnologia #palestra académica
            </div> 
        </div>
        <div class="boxed">
                <div class="hora">
                    5:00pm
                </div> 
                <img :src="require('@/assets/bienio.png')"/>
                <div class="title">           
                    Aula de desenvolvimento de solucoes medico hospitarais
                </div> 
                <div class="descripcao">
                        Prof:  </br>
                        Sala: PRO s.10       
                </div> 
                <div class="tags">
                    #aula
                </div> 
            </div>
</div>
</template>

<script>
import HomepageHeader from '../components/HomepageHeader.vue'

export default {
  components: {
    HomepageHeader
  }
}
</script>
