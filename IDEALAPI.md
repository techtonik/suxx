### Console

##### Read a name from input

`Bash is ideal` and solves this perfectly:

    read NAME
    
This stores everything that you've entered until you hit ENTER key in
variable $NAME. Newlines are not included. 

`Python` way:

    import sys
    PY3K = sys.version_info[0] == 3
    if not PY3K:
      name = raw_input()
    else:
      name = input()

There should be one-- and preferably only one --obvious way to do it. `Python` way `no.2`:

    import sys
    name = sys.stdin.readline().rstrip('\n')

`Ideal Python` way:

    import console
    console.read()

Any Go, Ruby, Rust examples? Pitfalls and bargains?
