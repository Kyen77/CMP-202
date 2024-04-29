public class User {
    String username = "kyen";
    String password = "Pass";
    String login() {
        if (username.equals("kyen") && password.equals("Pass")) {
            return "Logged in";
        } else {
            return "Failed";
        }
    }
    public static void main(String[] args) {
        User favour = new User();
        System.out.println(favour.login());
    }
}# CMP-202
Optional
