# otp-sni-hostname

Terminal 1:

```
./setup.sh
./run-tls-server.sh
```

Terminal 2:


```
./run-tls-client.sh
```

Expected:

I expect the `sni_hostname` to always be associated with a connection. Instead, it is only associated when either `sni_fun` or `sni_hosts` are set as TLS options.
