var  vm = new Vue({
   el: '#test',
   data: {
      mensaje: 'Ingrese el sitio a explorar',
      mensaje2: '',
      sitio: ''
   },
   methods: {
       enviar: function(event){
           return this.mensaje2 = this.sitio;
       }
    },
   computed: {
     }
})