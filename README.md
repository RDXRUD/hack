# hack

AAAAC3NzaC1lZDI1NTE5AAAAINPkWj1sdqMy7bw7ZHN34OLcj0gRdYC1MdmMQhs9wrl2


ssh -v user@10.202.46.14
OpenSSH_9.8p1, LibreSSL 3.3.6
debug1: Reading configuration data /Users/rudrakshagarwal/.ssh/config
debug1: Reading configuration data /etc/ssh/ssh_config
debug1: /etc/ssh/ssh_config line 21: include /etc/ssh/ssh_config.d/* matched no files
debug1: /etc/ssh/ssh_config line 54: Applying options for *
debug1: Authenticator provider $SSH_SK_PROVIDER did not resolve; disabling
debug1: Connecting to 10.202.46.14 [10.202.46.14] port 22.
debug1: Connection established.
debug1: identity file /Users/rudrakshagarwal/.ssh/id_rsa type 0
debug1: identity file /Users/rudrakshagarwal/.ssh/id_rsa-cert type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_ecdsa type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_ecdsa-cert type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_ecdsa_sk type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_ecdsa_sk-cert type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_ed25519 type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_ed25519-cert type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_ed25519_sk type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_ed25519_sk-cert type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_xmss type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_xmss-cert type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_dsa type -1
debug1: identity file /Users/rudrakshagarwal/.ssh/id_dsa-cert type -1
debug1: Local version string SSH-2.0-OpenSSH_9.8
debug1: Remote protocol version 2.0, remote software version OpenSSH_for_Windows_9.5
debug1: compat_banner: match: OpenSSH_for_Windows_9.5 pat OpenSSH* compat 0x04000000
debug1: Authenticating to 10.202.46.14:22 as 'user'
debug1: load_hostkeys: fopen /Users/rudrakshagarwal/.ssh/known_hosts2: No such file or directory
debug1: load_hostkeys: fopen /etc/ssh/ssh_known_hosts: No such file or directory
debug1: load_hostkeys: fopen /etc/ssh/ssh_known_hosts2: No such file or directory
debug1: SSH2_MSG_KEXINIT sent
debug1: SSH2_MSG_KEXINIT received
debug1: kex: algorithm: curve25519-sha256
debug1: kex: host key algorithm: ssh-ed25519
debug1: kex: server->client cipher: chacha20-poly1305@openssh.com MAC: <implicit> compression: none
debug1: kex: client->server cipher: chacha20-poly1305@openssh.com MAC: <implicit> compression: none
debug1: expecting SSH2_MSG_KEX_ECDH_REPLY
debug1: SSH2_MSG_KEX_ECDH_REPLY received
debug1: Server host key: ssh-ed25519 SHA256:Nn9HEnEH0lwGri709aRt7fAZrdzRIrostbVujgFTyHY
debug1: load_hostkeys: fopen /Users/rudrakshagarwal/.ssh/known_hosts2: No such file or directory
debug1: load_hostkeys: fopen /etc/ssh/ssh_known_hosts: No such file or directory
debug1: load_hostkeys: fopen /etc/ssh/ssh_known_hosts2: No such file or directory
debug1: Host '10.202.46.14' is known and matches the ED25519 host key.
debug1: Found key in /Users/rudrakshagarwal/.ssh/known_hosts:17
debug1: ssh_packet_send2_wrapped: resetting send seqnr 3
debug1: rekey out after 134217728 blocks
debug1: SSH2_MSG_NEWKEYS sent
debug1: expecting SSH2_MSG_NEWKEYS
debug1: ssh_packet_read_poll2: resetting read seqnr 3
debug1: SSH2_MSG_NEWKEYS received
debug1: rekey in after 134217728 blocks
debug1: SSH2_MSG_EXT_INFO received
debug1: kex_ext_info_client_parse: server-sig-algs=<ssh-ed25519,sk-ssh-ed25519@openssh.com,ecdsa-sha2-nistp256,ecdsa-sha2-nistp384,ecdsa-sha2-nistp521,sk-ecdsa-sha2-nistp256@openssh.com,webauthn-sk-ecdsa-sha2-nistp256@openssh.com,ssh-dss,ssh-rsa,rsa-sha2-256,rsa-sha2-512>
debug1: kex_ext_info_check_ver: publickey-hostbound@openssh.com=<0>
debug1: kex_ext_info_check_ver: ping@openssh.com=<0>
debug1: SSH2_MSG_SERVICE_ACCEPT received
debug1: Authentications that can continue: publickey,password,keyboard-interactive
debug1: Next authentication method: publickey
debug1: get_agent_identities: bound agent to hostkey
debug1: get_agent_identities: ssh_fetch_identitylist: agent contains no identities
debug1: Will attempt key: /Users/rudrakshagarwal/.ssh/id_rsa RSA SHA256:Y5o/LxLkD1xeo2sKaYcpe236WyopGQ4RUT/nalG9hNk
debug1: Will attempt key: /Users/rudrakshagarwal/.ssh/id_ecdsa 
debug1: Will attempt key: /Users/rudrakshagarwal/.ssh/id_ecdsa_sk 
debug1: Will attempt key: /Users/rudrakshagarwal/.ssh/id_ed25519 
debug1: Will attempt key: /Users/rudrakshagarwal/.ssh/id_ed25519_sk 
debug1: Will attempt key: /Users/rudrakshagarwal/.ssh/id_xmss 
debug1: Will attempt key: /Users/rudrakshagarwal/.ssh/id_dsa 
debug1: Offering public key: /Users/rudrakshagarwal/.ssh/id_rsa RSA SHA256:Y5o/LxLkD1xeo2sKaYcpe236WyopGQ4RUT/nalG9hNk
debug1: Authentications that can continue: publickey,password,keyboard-interactive
debug1: Trying private key: /Users/rudrakshagarwal/.ssh/id_ecdsa
debug1: Trying private key: /Users/rudrakshagarwal/.ssh/id_ecdsa_sk
debug1: Trying private key: /Users/rudrakshagarwal/.ssh/id_ed25519
debug1: Trying private key: /Users/rudrakshagarwal/.ssh/id_ed25519_sk
debug1: Trying private key: /Users/rudrakshagarwal/.ssh/id_xmss
debug1: Trying private key: /Users/rudrakshagarwal/.ssh/id_dsa
debug1: Next authentication method: keyboard-interactive
debug1: Authentications that can continue: publickey,password,keyboard-interactive
debug1: Next authentication method: password
user@10.202.46.14's password: 
