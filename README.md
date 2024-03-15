public class Main {
    public static void main(String[] args) {
        // Création de l'arbre binaire vide
        ArbreBinaire arbre = ArbreBinaire.creer();
        
        // Insertion de valeurs dans l'arbre
        arbre.inserer(5);
        arbre.inserer(3);
        arbre.inserer(8);
        arbre.inserer(1);
        arbre.inserer(4);
        arbre.inserer(7);
        arbre.inserer(10);
        
        // Affichage de l'arbre après l'insertion des valeurs
        arbre.afficher();
        System.out.println();
    }
}
