# sqa-assign-

public class SearchModule {
    public static void main(String[] args) {
        String[] selections = {"sales", "finance", "marketing"};

        for (String selection : selections) {
            System.out.println("Searching in category: " + selection);

            switch (selection) {
                case "sales":
                    System.out.println("Displaying Sales Report...");
                    break;
                case "inventory":
                    System.out.println("Displaying Inventory Data...");
                    break;
                case "finance":
                    System.out.println("Displaying Finance Summary...");
                    break;
                default:
                    System.out.println("Invalid category. please try again.");
            }

            System.out.println("Search complete.\n");
        }
    }
}
