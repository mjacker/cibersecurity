# Creating passwords

`pwgen 48 -sync -1`

Saving new generated password
`pass insert Sites/Example.com`

Retrieving password
`pass Sites/Example.com -c`

`openssl rand -base64 48`
