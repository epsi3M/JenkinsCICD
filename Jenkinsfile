pipeline{
	agent any
	stages{
	stage('Budgets'){
	steps{
		input('Voulez-vous poursuivre ?')
		echo "Budgets etablis !"
		
	}
	}
	stage('Allocations'){
	steps{
		
		echo "Allocations gerees"
	}
	}
	stage('Consolidation'){
	steps{
		
		echo "Consolidation effectuee !"
	}
	}
	stage('Gestion des commandes'){
	steps{
		
		echo "L'acheminement des commandes a bien ete effectue !"
	}
	}
	stage('Gestion qualite'){
	steps{
		
		echo "Produit(s) conforme(s) au(x) besoin(s) du client !"
	}
	}
	stage('Enregistrement des cheques'){
	steps{
		input('Voulez-vous poursuivre ?')
		echo "les cheques ont bien ete enregistre ! "
	}
	}
	stage('Gestion des paiements'){
	steps{
		
		echo "le client a realise un paiement par cheques"
	}
	}
	stage('Facture'){
	steps{
		input('Voulez-vous poursuivre ?')
		echo "Facture etablie !"
	}
	}
	}
}
