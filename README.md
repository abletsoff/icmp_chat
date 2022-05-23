# icmp_chat
Python implementation of the ICMP coverd communication

# Functionality
<pre> 

optional arguments:
  -h, --help            show this help message and exit
  -f FILENAME, --filename FILENAME
                        filename to transmit / recive
  -t TEXT, --text TEXT  text string to transmit
  -H HOST, --host HOST  host to transmit / listen from
  -l, --listen          listen mode
  -L, --logging         Detailed logging
  -s SIZE, --size SIZE  max size of payload for one icmp packet
  -T TYPE, --type TYPE  icmp type
  -O OPCODE, --opcode OPCODE
                        icmp opcode
  -A, --all_icmp        listen for all ICMP types and opcodes. Do not use this
                        option while listening ECHO request
</pre>

# Example
![PoC](https://github.com/abletsoff/icmp_chat/blob/main/PoC_2.png?raw=true)
