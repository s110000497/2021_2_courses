# Linux
```
curl -h
Usage: curl [options...] <url>
Options: (H) means HTTP/HTTPS only, (F) means FTP only
     --anyauth       Pick "any" authentication method (H)
 -a, --append        Append to target file when uploading (F/SFTP)
     --basic         Use HTTP Basic Authentication (H)
     --cacert FILE   CA certificate to verify peer against (SSL)
     --capath DIR    CA directory to verify peer against (SSL)
 -E, --cert CERT[:PASSWD]  Client certificate file and password (SSL)
     --cert-status   Verify the status of the server certificate (SSL)
     --cert-type TYPE  Certificate file type (DER/PEM/ENG) (SSL)
     --ciphers LIST  SSL ciphers to use (SSL)
     --compressed    Request compressed response (using deflate or gzip)
 -K, --config FILE   Read config from FILE
     --connect-timeout SECONDS  Maximum time allowed for connection
 -C, --continue-at OFFSET  Resumed transfer OFFSET
 -b, --cookie STRING/FILE  Read cookies from STRING/FILE (H)
 -c, --cookie-jar FILE  Write cookies to FILE after operation (H)
     --create-dirs   Create necessary local directory hierarchy
     --crlf          Convert LF to CRLF in upload
     --crlfile FILE  Get a CRL list in PEM format from the given file
 -d, --data DATA     HTTP POST data (H)
     --data-raw DATA  HTTP POST data, '@' allowed (H)
     --data-ascii DATA  HTTP POST ASCII data (H)
     --data-binary DATA  HTTP POST binary data (H)
     --data-urlencode DATA  HTTP POST data url encoded (H)
     --delegation STRING  GSS-API delegation permission
     --digest        Use HTTP Digest Authentication (H)
     --disable-eprt  Inhibit using EPRT or LPRT (F)
     --disable-epsv  Inhibit using EPSV (F)
     --dns-servers   DNS server addrs to use: 1.1.1.1;2.2.2.2
     --dns-interface  Interface to use for DNS requests
     --dns-ipv4-addr  IPv4 address to use for DNS requests, dot notation
     --dns-ipv6-addr  IPv6 address to use for DNS requests, dot notation
 -D, --dump-header FILE  Write the headers to FILE
     --egd-file FILE  EGD socket path for random data (SSL)
     --engine ENGINE  Crypto engine (use "--engine list" for list) (SSL)
     --expect100-timeout SECONDS How long to wait for 100-continue (H)
 -f, --fail          Fail silently (no output at all) on HTTP errors (H)
     --false-start   Enable TLS False Start.
 -F, --form CONTENT  Specify HTTP multipart POST data (H)
     --form-string STRING  Specify HTTP multipart POST data (H)
     --ftp-account DATA  Account data string (F)
     --ftp-alternative-to-user COMMAND  String to replace "USER [name]" (F)
     --ftp-create-dirs  Create the remote dirs if not present (F)
     --ftp-method [MULTICWD/NOCWD/SINGLECWD]  Control CWD usage (F)
     --ftp-pasv      Use PASV/EPSV instead of PORT (F)
 -P, --ftp-port ADR  Use PORT with given address instead of PASV (F)
     --ftp-skip-pasv-ip  Skip the IP address for PASV (F)
     --ftp-pret      Send PRET before PASV (for drftpd) (F)
     --ftp-ssl-ccc   Send CCC after authenticating (F)
     --ftp-ssl-ccc-mode ACTIVE/PASSIVE  Set CCC mode (F)
     --ftp-ssl-control  Require SSL/TLS for FTP login, clear for transfer (F)
 -G, --get           Send the -d data with a HTTP GET (H)
 -g, --globoff       Disable URL sequences and ranges using {} and []
 -H, --header LINE   Pass custom header LINE to server (H)
 -I, --head          Show document info only
 -h, --help          This help text
     --hostpubmd5 MD5  Hex-encoded MD5 string of the host public key. (SSH)
 -0, --http1.0       Use HTTP 1.0 (H)
     --http1.1       Use HTTP 1.1 (H)
     --http2         Use HTTP 2 (H)
     --ignore-content-length  Ignore the HTTP Content-Length header
 -i, --include       Include protocol headers in the output (H/F)
 -k, --insecure      Allow connections to SSL sites without certs (H)
     --interface INTERFACE  Use network INTERFACE (or address)
 -4, --ipv4          Resolve name to IPv4 address
 -6, --ipv6          Resolve name to IPv6 address
 -j, --junk-session-cookies  Ignore session cookies read from file (H)
     --keepalive-time SECONDS  Wait SECONDS between keepalive probes
     --key KEY       Private key file name (SSL/SSH)
     --key-type TYPE  Private key file type (DER/PEM/ENG) (SSL)
     --krb LEVEL     Enable Kerberos with security LEVEL (F)
     --libcurl FILE  Dump libcurl equivalent code of this command line
     --limit-rate RATE  Limit transfer speed to RATE
 -l, --list-only     List only mode (F/POP3)
     --local-port RANGE  Force use of RANGE for local port numbers
 -L, --location      Follow redirects (H)
     --location-trusted  Like '--location', and send auth to other hosts (H)
     --login-options OPTIONS  Server login options (IMAP, POP3, SMTP)
 -M, --manual        Display the full manual
     --mail-from FROM  Mail from this address (SMTP)
     --mail-rcpt TO  Mail to this/these addresses (SMTP)
     --mail-auth AUTH  Originator address of the original email (SMTP)
     --max-filesize BYTES  Maximum file size to download (H/F)
     --max-redirs NUM  Maximum number of redirects allowed (H)
 -m, --max-time SECONDS  Maximum time allowed for the transfer
     --metalink      Process given URLs as metalink XML file
     --negotiate     Use HTTP Negotiate (SPNEGO) authentication (H)
 -n, --netrc         Must read .netrc for user name and password
     --netrc-optional  Use either .netrc or URL; overrides -n
     --netrc-file FILE  Specify FILE for netrc
 -:, --next          Allows the following URL to use a separate set of options
     --no-alpn       Disable the ALPN TLS extension (H)
 -N, --no-buffer     Disable buffering of the output stream
     --no-keepalive  Disable keepalive use on the connection
     --no-npn        Disable the NPN TLS extension (H)
     --no-sessionid  Disable SSL session-ID reusing (SSL)
     --noproxy       List of hosts which do not use proxy
     --ntlm          Use HTTP NTLM authentication (H)
     --oauth2-bearer TOKEN  OAuth 2 Bearer Token (IMAP, POP3, SMTP)
 -o, --output FILE   Write to FILE instead of stdout
     --pass PASS     Pass phrase for the private key (SSL/SSH)
     --path-as-is    Do not squash .. sequences in URL path
     --pinnedpubkey FILE/HASHES Public key to verify peer against (SSL)
     --post301       Do not switch to GET after following a 301 redirect (H)
     --post302       Do not switch to GET after following a 302 redirect (H)
     --post303       Do not switch to GET after following a 303 redirect (H)
 -#, --progress-bar  Display transfer progress as a progress bar
     --proto PROTOCOLS  Enable/disable PROTOCOLS
     --proto-default PROTOCOL  Use PROTOCOL for any URL missing a scheme
     --proto-redir PROTOCOLS   Enable/disable PROTOCOLS on redirect
 -x, --proxy [PROTOCOL://]HOST[:PORT]  Use proxy on given port
     --proxy-anyauth  Pick "any" proxy authentication method (H)
     --proxy-basic   Use Basic authentication on the proxy (H)
     --proxy-digest  Use Digest authentication on the proxy (H)
     --proxy-negotiate  Use HTTP Negotiate (SPNEGO) authentication on the proxy (H)
     --proxy-ntlm    Use NTLM authentication on the proxy (H)
     --proxy-service-name NAME  SPNEGO proxy service name
     --service-name NAME  SPNEGO service name
 -U, --proxy-user USER[:PASSWORD]  Proxy user and password
     --proxy1.0 HOST[:PORT]  Use HTTP/1.0 proxy on given port
 -p, --proxytunnel   Operate through a HTTP proxy tunnel (using CONNECT)
     --pubkey KEY    Public key file name (SSH)
 -Q, --quote CMD     Send command(s) to server before transfer (F/SFTP)
     --random-file FILE  File for reading random data from (SSL)
 -r, --range RANGE   Retrieve only the bytes within RANGE
     --raw           Do HTTP "raw"; no transfer decoding (H)
 -e, --referer       Referer URL (H)
 -J, --remote-header-name  Use the header-provided filename (H)
 -O, --remote-name   Write output to a file named as the remote file
     --remote-name-all  Use the remote file name for all URLs
 -R, --remote-time   Set the remote file's time on the local output
 -X, --request COMMAND  Specify request command to use
     --resolve HOST:PORT:ADDRESS  Force resolve of HOST:PORT to ADDRESS
     --retry NUM   Retry request NUM times if transient problems occur
     --retry-delay SECONDS  Wait SECONDS between retries
     --retry-max-time SECONDS  Retry only within this period
     --sasl-ir       Enable initial response in SASL authentication
 -S, --show-error    Show error. With -s, make curl show errors when they occur
 -s, --silent        Silent mode (don't output anything)
     --socks4 HOST[:PORT]  SOCKS4 proxy on given host + port
     --socks4a HOST[:PORT]  SOCKS4a proxy on given host + port
     --socks5 HOST[:PORT]  SOCKS5 proxy on given host + port
     --socks5-hostname HOST[:PORT]  SOCKS5 proxy, pass host name to proxy
     --socks5-gssapi-service NAME  SOCKS5 proxy service name for GSS-API
     --socks5-gssapi-nec  Compatibility with NEC SOCKS5 server
 -Y, --speed-limit RATE  Stop transfers below RATE for 'speed-time' secs
 -y, --speed-time SECONDS  Trigger 'speed-limit' abort after SECONDS (default: 30)
     --ssl           Try SSL/TLS (FTP, IMAP, POP3, SMTP)
     --ssl-reqd      Require SSL/TLS (FTP, IMAP, POP3, SMTP)
 -2, --sslv2         Use SSLv2 (SSL)
 -3, --sslv3         Use SSLv3 (SSL)
     --ssl-allow-beast  Allow security flaw to improve interop (SSL)
     --ssl-no-revoke    Disable cert revocation checks (WinSSL)
     --stderr FILE   Where to redirect stderr (use "-" for stdout)
     --tcp-nodelay   Use the TCP_NODELAY option
 -t, --telnet-option OPT=VAL  Set telnet option
     --tftp-blksize VALUE  Set TFTP BLKSIZE option (must be >512)
 -z, --time-cond TIME  Transfer based on a time condition
 -1, --tlsv1         Use >= TLSv1 (SSL)
     --tlsv1.0       Use TLSv1.0 (SSL)
     --tlsv1.1       Use TLSv1.1 (SSL)
     --tlsv1.2       Use TLSv1.2 (SSL)
     --trace FILE    Write a debug trace to FILE
     --trace-ascii FILE  Like --trace, but without hex output
     --trace-time    Add time stamps to trace/verbose output
     --tr-encoding   Request compressed transfer encoding (H)
 -T, --upload-file FILE  Transfer FILE to destination
     --url URL       URL to work with
 -B, --use-ascii     Use ASCII/text transfer
 -u, --user USER[:PASSWORD]  Server user and password
     --tlsuser USER  TLS username
     --tlspassword STRING  TLS password
     --tlsauthtype STRING  TLS authentication type (default: SRP)
     --unix-socket FILE    Connect through this Unix domain socket
 -A, --user-agent STRING  Send User-Agent STRING to server (H)
 -v, --verbose       Make the operation more talkative
 -V, --version       Show version number and quit
 -w, --write-out FORMAT  Use output FORMAT after completion
     --xattr         Store metadata in extended file attributes
 -q                  Disable .curlrc (must be first parameter)

```
# Windows

```
C:\Windows\system32>curl -h
Usage: curl [options...] <url>
     --abstract-unix-socket <path> Connect via abstract Unix domain socket
     --anyauth       Pick any authentication method
 -a, --append        Append to target file when uploading
     --basic         Use HTTP Basic Authentication
     --cacert <CA certificate> CA certificate to verify peer against
     --capath <dir>  CA directory to verify peer against
 -E, --cert <certificate[:password]> Client certificate file and password
     --cert-status   Verify the status of the server certificate
     --cert-type <type> Certificate file type (DER/PEM/ENG)
     --ciphers <list of ciphers> SSL ciphers to use
     --compressed    Request compressed response
 -K, --config <file> Read config from a file
     --connect-timeout <seconds> Maximum time allowed for connection
     --connect-to <HOST1:PORT1:HOST2:PORT2> Connect to host
 -C, --continue-at <offset> Resumed transfer offset
 -b, --cookie <data> Send cookies from string/file
 -c, --cookie-jar <filename> Write cookies to <filename> after operation
     --create-dirs   Create necessary local directory hierarchy
     --crlf          Convert LF to CRLF in upload
     --crlfile <file> Get a CRL list in PEM format from the given file
 -d, --data <data>   HTTP POST data
     --data-ascii <data> HTTP POST ASCII data
     --data-binary <data> HTTP POST binary data
     --data-raw <data> HTTP POST data, '@' allowed
     --data-urlencode <data> HTTP POST data url encoded
     --delegation <LEVEL> GSS-API delegation permission
     --digest        Use HTTP Digest Authentication
 -q, --disable       Disable .curlrc
     --disable-eprt  Inhibit using EPRT or LPRT
     --disable-epsv  Inhibit using EPSV
     --dns-interface <interface> Interface to use for DNS requests
     --dns-ipv4-addr <address> IPv4 address to use for DNS requests
     --dns-ipv6-addr <address> IPv6 address to use for DNS requests
     --dns-servers <addresses> DNS server addrs to use
 -D, --dump-header <filename> Write the received headers to <filename>
     --egd-file <file> EGD socket path for random data
     --engine <name> Crypto engine to use
     --expect100-timeout <seconds> How long to wait for 100-continue
 -f, --fail          Fail silently (no output at all) on HTTP errors
     --fail-early    Fail on first transfer error, do not continue
     --false-start   Enable TLS False Start
 -F, --form <name=content> Specify HTTP multipart POST data
     --form-string <name=string> Specify HTTP multipart POST data
     --ftp-account <data> Account data string
     --ftp-alternative-to-user <command> String to replace USER [name]
     --ftp-create-dirs Create the remote dirs if not present
     --ftp-method <method> Control CWD usage
     --ftp-pasv      Use PASV/EPSV instead of PORT
 -P, --ftp-port <address> Use PORT instead of PASV
     --ftp-pret      Send PRET before PASV
     --ftp-skip-pasv-ip Skip the IP address for PASV
     --ftp-ssl-ccc   Send CCC after authenticating
     --ftp-ssl-ccc-mode <active/passive> Set CCC mode
     --ftp-ssl-control Require SSL/TLS for FTP login, clear for transfer
 -G, --get           Put the post data in the URL and use GET
 -g, --globoff       Disable URL sequences and ranges using {} and []
 -I, --head          Show document info only
 -H, --header <header/@file> Pass custom header(s) to server
 -h, --help          This help text
     --hostpubmd5 <md5> Acceptable MD5 hash of the host public key
 -0, --http1.0       Use HTTP 1.0
     --http1.1       Use HTTP 1.1
     --http2         Use HTTP 2
     --http2-prior-knowledge Use HTTP 2 without HTTP/1.1 Upgrade
     --ignore-content-length Ignore the size of the remote resource
 -i, --include       Include protocol response headers in the output
 -k, --insecure      Allow insecure server connections when using SSL
     --interface <name> Use network INTERFACE (or address)
 -4, --ipv4          Resolve names to IPv4 addresses
 -6, --ipv6          Resolve names to IPv6 addresses
 -j, --junk-session-cookies Ignore session cookies read from file
     --keepalive-time <seconds> Interval time for keepalive probes
     --key <key>     Private key file name
     --key-type <type> Private key file type (DER/PEM/ENG)
     --krb <level>   Enable Kerberos with security <level>
     --libcurl <file> Dump libcurl equivalent code of this command line
     --limit-rate <speed> Limit transfer speed to RATE
 -l, --list-only     List only mode
     --local-port <num/range> Force use of RANGE for local port numbers
 -L, --location      Follow redirects
     --location-trusted Like --location, and send auth to other hosts
     --login-options <options> Server login options
     --mail-auth <address> Originator address of the original email
     --mail-from <address> Mail from this address
     --mail-rcpt <address> Mail from this address
 -M, --manual        Display the full manual
     --max-filesize <bytes> Maximum file size to download
     --max-redirs <num> Maximum number of redirects allowed
 -m, --max-time <time> Maximum time allowed for the transfer
     --metalink      Process given URLs as metalink XML file
     --negotiate     Use HTTP Negotiate (SPNEGO) authentication
 -n, --netrc         Must read .netrc for user name and password
     --netrc-file <filename> Specify FILE for netrc
     --netrc-optional Use either .netrc or URL
 -:, --next          Make next URL use its separate set of options
     --no-alpn       Disable the ALPN TLS extension
 -N, --no-buffer     Disable buffering of the output stream
     --no-keepalive  Disable TCP keepalive on the connection
     --no-npn        Disable the NPN TLS extension
     --no-sessionid  Disable SSL session-ID reusing
     --noproxy <no-proxy-list> List of hosts which do not use proxy
     --ntlm          Use HTTP NTLM authentication
     --ntlm-wb       Use HTTP NTLM authentication with winbind
     --oauth2-bearer <token> OAuth 2 Bearer Token
 -o, --output <file> Write to file instead of stdout
     --pass <phrase> Pass phrase for the private key
     --path-as-is    Do not squash .. sequences in URL path
     --pinnedpubkey <hashes> FILE/HASHES Public key to verify peer against
     --post301       Do not switch to GET after following a 301
     --post302       Do not switch to GET after following a 302
     --post303       Do not switch to GET after following a 303
     --preproxy [protocol://]host[:port] Use this proxy first
 -#, --progress-bar  Display transfer progress as a bar
     --proto <protocols> Enable/disable PROTOCOLS
     --proto-default <protocol> Use PROTOCOL for any URL missing a scheme
     --proto-redir <protocols> Enable/disable PROTOCOLS on redirect
 -x, --proxy [protocol://]host[:port] Use this proxy
     --proxy-anyauth Pick any proxy authentication method
     --proxy-basic   Use Basic authentication on the proxy
     --proxy-cacert <file> CA certificate to verify peer against for proxy
     --proxy-capath <dir> CA directory to verify peer against for proxy
     --proxy-cert <cert[:passwd]> Set client certificate for proxy
     --proxy-cert-type <type> Client certificate type for HTTS proxy
     --proxy-ciphers <list> SSL ciphers to use for proxy
     --proxy-crlfile <file> Set a CRL list for proxy
     --proxy-digest  Use Digest authentication on the proxy
     --proxy-header <header/@file> Pass custom header(s) to proxy
     --proxy-insecure Do HTTPS proxy connections without verifying the proxy
     --proxy-key <key> Private key for HTTPS proxy
     --proxy-key-type <type> Private key file type for proxy
     --proxy-negotiate Use HTTP Negotiate (SPNEGO) authentication on the proxy
     --proxy-ntlm    Use NTLM authentication on the proxy
     --proxy-pass <phrase> Pass phrase for the private key for HTTPS proxy
     --proxy-service-name <name> SPNEGO proxy service name
     --proxy-ssl-allow-beast Allow security flaw for interop for HTTPS proxy
     --proxy-tlsauthtype <type> TLS authentication type for HTTPS proxy
     --proxy-tlspassword <string> TLS password for HTTPS proxy
     --proxy-tlsuser <name> TLS username for HTTPS proxy
     --proxy-tlsv1   Use TLSv1 for HTTPS proxy
 -U, --proxy-user <user:password> Proxy user and password
     --proxy1.0 <host[:port]> Use HTTP/1.0 proxy on given port
 -p, --proxytunnel   Operate through a HTTP proxy tunnel (using CONNECT)
     --pubkey <key>  SSH Public key file name
 -Q, --quote         Send command(s) to server before transfer
     --random-file <file> File for reading random data from
 -r, --range <range> Retrieve only the bytes within RANGE
     --raw           Do HTTP "raw"; no transfer decoding
 -e, --referer <URL> Referrer URL
 -J, --remote-header-name Use the header-provided filename
 -O, --remote-name   Write output to a file named as the remote file
     --remote-name-all Use the remote file name for all URLs
 -R, --remote-time   Set the remote file's time on the local output
 -X, --request <command> Specify request command to use
     --request-target Specify the target for this request
     --resolve <host:port:address> Resolve the host+port to this address
     --retry <num>   Retry request if transient problems occur
     --retry-connrefused Retry on connection refused (use with --retry)
     --retry-delay <seconds> Wait time between retries
     --retry-max-time <seconds> Retry only within this period
     --sasl-ir       Enable initial response in SASL authentication
     --service-name <name> SPNEGO service name
 -S, --show-error    Show error even when -s is used
 -s, --silent        Silent mode
     --socks4 <host[:port]> SOCKS4 proxy on given host + port
     --socks4a <host[:port]> SOCKS4a proxy on given host + port
     --socks5 <host[:port]> SOCKS5 proxy on given host + port
     --socks5-basic  Enable username/password auth for SOCKS5 proxies
     --socks5-gssapi Enable GSS-API auth for SOCKS5 proxies
     --socks5-gssapi-nec Compatibility with NEC SOCKS5 server
     --socks5-gssapi-service <name> SOCKS5 proxy service name for GSS-API
     --socks5-hostname <host[:port]> SOCKS5 proxy, pass host name to proxy
 -Y, --speed-limit <speed> Stop transfers slower than this
 -y, --speed-time <seconds> Trigger 'speed-limit' abort after this time
     --ssl           Try SSL/TLS
     --ssl-allow-beast Allow security flaw to improve interop
     --ssl-no-revoke Disable cert revocation checks (WinSSL)
     --ssl-reqd      Require SSL/TLS
 -2, --sslv2         Use SSLv2
 -3, --sslv3         Use SSLv3
     --stderr        Where to redirect stderr
     --suppress-connect-headers Suppress proxy CONNECT response headers
     --tcp-fastopen  Use TCP Fast Open
     --tcp-nodelay   Use the TCP_NODELAY option
 -t, --telnet-option <opt=val> Set telnet option
     --tftp-blksize <value> Set TFTP BLKSIZE option
     --tftp-no-options Do not send any TFTP options
 -z, --time-cond <time> Transfer based on a time condition
     --tls-max <VERSION> Use TLSv1.0 or greater
     --tlsauthtype <type> TLS authentication type
     --tlspassword   TLS password
     --tlsuser <name> TLS user name
 -1, --tlsv1         Use TLSv1.0 or greater
     --tlsv1.0       Use TLSv1.0
     --tlsv1.1       Use TLSv1.1
     --tlsv1.2       Use TLSv1.2
     --tlsv1.3       Use TLSv1.3
     --tr-encoding   Request compressed transfer encoding
     --trace <file>  Write a debug trace to FILE
     --trace-ascii <file> Like --trace, but without hex output
     --trace-time    Add time stamps to trace/verbose output
     --unix-socket <path> Connect through this Unix domain socket
 -T, --upload-file <file> Transfer local FILE to destination
     --url <url>     URL to work with
 -B, --use-ascii     Use ASCII/text transfer
 -u, --user <user:password> Server user and password
 -A, --user-agent <name> Send User-Agent <name> to server
 -v, --verbose       Make the operation more talkative
 -V, --version       Show version number and quit
 -w, --write-out <format> Use output FORMAT after completion
     --xattr         Store metadata in extended file attributes

```
