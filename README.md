feat: Implement user configuration management for git
 • Add User struct with methods to insert values and convert indices to keys
 • Implement use_user function to switch git config to a specified user
 • Create set_user function to apply User struct values to git config
 • Add find_user_in_config to locate and prepare user section for updates
 • Utilize external crates for colorization and serialization
 • Handle edge cases such as missing git config and non-existent users
