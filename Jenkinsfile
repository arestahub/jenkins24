pipeline
{
  agent any
    environment
    {
        SEMANA = 'lunes,martes,miercoles,jueves,viernes,sabado,domingo'
        DIA = 'martes'
    }
  stages
  {
    stage("Los dias de la semana")
    {
      steps
      {
			script
            {                    
                    println "La semana tiene los dias: ${SEMANA}"
                    println "Hoy dia es: ${DIA}"
            
      }
    }
  }
}
}
