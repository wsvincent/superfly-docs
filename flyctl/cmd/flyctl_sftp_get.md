The SFTP GET retrieves a file from a remote VM.

## Usage
~~~
flyctl sftp get <path> [flags]
~~~

## Options

~~~
  -A, --address string   Address of VM to connect to
  -a, --app string       Application name
  -C, --command string   command to run on SSH session
  -c, --config string    Path to application configuration file
  -h, --help             help for get
  -o, --org string       The organization to operate on
  -q, --quiet            Don't print progress indicators for WireGuard
  -r, --region string    Region to create WireGuard connection in
  -s, --select           select available instances
~~~

## Global Options

~~~
  -t, --access-token string   Fly API Access Token
  -j, --json                  json output
      --verbose               verbose output
~~~

## See Also

* [flyctl sftp](/docs/flyctl/sftp/)	 - Get or put files from a remote VM.

