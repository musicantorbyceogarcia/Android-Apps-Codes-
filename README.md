# Android-Apps-Codes-
Codigos de Curso Android Studio 



**
  Codigos desenvolvidos em Aula ADNROID STUDIO 
//  (onCreate )Metodos principal De Inicializacao 
// findViewById retorna um elemento do tipo VIEW
**


	String[] frases = {"O Mundo fala o mundo movem","Eu tinha planos como voce ",
	"acabou o bailão ","olha so como que esta os moleques"};


      btnTestar = (Button)findViewById(R.id.btnTestar);

	btnTestar.setOnClickListener(new View.OnClikcListener){
   	 @Override
	public  void onClick(View view){

			Random rand = new Random();
			int aleatorio =  rand.nextInt(frases.lenght);

			frases.setText(aleatorio);
		}




	}
}
