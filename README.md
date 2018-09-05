# Android-Apps-Codes-
Codigos de Curso Android Studio 



**
  Codigos desenvolvidos em Aula ADNROID STUDIO 

**


public class MainActivtiy(){

	private Button btnTestar;

	String[] frases = {"O Mundo fala o mundo movem","Eu tinha planos como voce ",
	"acabou o bailão ","olha so como que esta os moleques"};

  // Metodos principal De Inicializacao 
	public void onCreate(savedInstace){
		setContentView(R.id.activity_main);

      // recupero o botao / findViewById retorna um elemwnto do tipo VIEW
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
