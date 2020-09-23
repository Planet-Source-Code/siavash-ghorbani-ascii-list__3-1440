<div align="center">

## ASCII list


</div>

### Description

Show a list of the entire ASCII list...

Sometimes good to have. Just made the code for fun. Good to learn basics from.
 
### More Info
 
The ASCII list.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Siavash Ghorbani](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/siavash-ghorbani.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__3-32.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/siavash-ghorbani-ascii-list__3-1440/archive/master.zip)

### API Declarations

```
#include <iostream.h>
```


### Source Code

```
//ice_t@dosgames.com
//If you want this in a file just do: charlist.exe > charlog.txt
//I hope you can use it for something :)
#include <iostream.h>
int main()
{
for (int charnr = 0; charnr < 256; charnr++)
	cout << (char)charnr << " = " << charnr << "\n";
return 0;
}
```

