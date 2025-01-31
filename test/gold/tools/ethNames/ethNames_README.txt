ethNames argc: 2 [1:-th] 
ethNames -th 
### Usage

`Usage:`    chifra names [-e|-m|-l|-c|-p|-n|-a|-s|-g|-v|-h] &lt;term&gt; [term...]  
`Purpose:`  Query addresses or names of well known accounts.

`Where:`  

| | Option | Description |
| :----- | :----- | :---------- |
|  | terms | a space separated list of one or more search terms (required) |
| -e | --expand | expand search to include all fields (default searches name, address, and symbol only) |
| -m | --match_case | do case-sensitive search |
| -l | --all | include all accounts in the search |
| -c | --custom | include your custom named accounts |
| -p | --prefund | include prefund accounts |
| -n | --named | include well know token and airdrop addresses in the search |
| -a | --addr | display only addresses in the results (useful for scripting) |
| -s | --collections | display collections data |
| -g | --tags | export the list of tags and subtags only |
|####|Hidden options||
| -u | --to_custom | for editCmd only, is the edited name a custom name or not |
| -C | --clean | clean the data (addrs to lower case, sort by addr) |
| -A | --autoname &lt;str&gt; | an address assumed to be a token, added automatically to names database if true |
|####|Hidden options||
| -x | --fmt &lt;val&gt; | export format, one of *[ none \| json\* \| txt \| csv \| api ]* |
| -v | --verbose | set verbose level (optional level defaults to 1) |
| -h | --help | display this help screen |

`Notes:`

- The tool will accept up to three terms, each of which must match against any field in the database.
- The `--match_case` option enables case sensitive matching.

