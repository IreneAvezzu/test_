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
  Homepage-->Profile_page;
  Homepage-->All_items;
  Homepage-->Tops;
  Homepage-->Bottoms;
  Homepage-->Dresses;
  Homepage-->Accessorise;
  Homepage-->Favourites;
  Homepage-->Outfits;
  Homepage-->Add_page;
  Homepage-->Profile;
  Homepage-->About_us;
  Homepage-->App_information;
  Add_page-->Add_outfit;
  Add_page-->Add_item;
  Add_outfit-->Homepage;
  Add_item-->Homepage;
  Profile-->edit_account;
  Profile-->delete_account;
  Profile-->logout;
```
