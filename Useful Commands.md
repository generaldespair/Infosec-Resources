## Displaying shellcode that contains printable chars

`printf $(cat fake-payload.txt | tr -d '\n')`
