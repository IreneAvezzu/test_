# hello

# hi

```mermaid
graph TD;
  App_launch-->Load_application_from_json_file;
  Load_application_from_json_file-->Login_page;
  Login_page-->Sign_up;
  Sign_up-->Login_page;
  Login_page-->Login;
  Login-->Homepage;
  Homepage-->About_us;
  Homepage-->App_information;
  Homepage-->All_items;
  Homepage-->Tops;
  Homepage-->Bottoms;
  Homepage-->Dresses;
  Homepage-->Add_page;
  Homepage-->Accessorise;
  Homepage-->Favourites;
  Homepage-->Outfits;
  Homepage-->Profile;
  
  Add_page-->Add_outfit;
  Add_page-->Add_item;
  Profile-->edit_account;
  Profile-->delete_account;
  Profile-->logout;
```
