# GPG


######### TO SEND SECURE MESSAGE TO ME FOLLOW THE STEPS MENTIONED BELOW ##########

Step 1: Import the key to local keyring using following command:

gpg --import <public_key_Filename.extension>

Step 2: Do the encryption:

gpg --output <out_filename>.gpg --encrypt --recipient kkpuneet@gmail.com <file_name_to_be_encrypted>


----------------------------------------- OR ----------------------------------------------------------

My public key is also Uploaded to: http://hkps.pool.sks-keyservers.net/

You can find it on keyserver using command: 
gpg --keyserver http://hkps.pool.sks-keyservers.net/ --search-key <fingerprint_shared_through_email>

Import the key to local keyring from keyserver (Depends on keyserver. May not work at times.)

Step 1:

gpg --keyserver http://hkps.pool.sks-keyservers.net/ --recv-keys <key_id>

Step 2:

gpg --output <out_filename>.gpg --encrypt --recipient kkpuneet@gmail.com <file_name_to_be_encrypted>



### Thanks ###

Stay Safe :)
