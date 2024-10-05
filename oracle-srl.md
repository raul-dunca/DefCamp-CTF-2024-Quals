<img src="https://github.com/raul-dunca/assets/blob/main/.images_Defcamp_2024_Quals/oracle-srl.png?raw=true">

The zip file provided by the challenge seems to contain two versions of the same web application, which is kind of weird. After inspecting both, it seems that in one (in the `client.go` file) there is the flag lying around, whereas in the other is deleted. I think this was 100% a mistake, and the author forgot to delete the version with the flag inside.

`CTF{e663b007e3d1fd27f657e2756e3ba8724a37119d145063ce541595988b6cdc72}`
