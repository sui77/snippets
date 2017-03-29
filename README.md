# snippets

transparent gif
---------------

<code>
data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7
</code>

haproxy configtest
------------------

<code>
haproxy -c -f /etc/haproxy/haproxy.cfg
</code>

diff brief, recursive, ignorewhitespace
---------------------------------------

<code>
diff -qrw /tmp/a /tmp/b
</code>

install percona@ubuntu
----------------------
wget https://repo.percona.com/apt/percona-release_0.1-4.$(lsb_release -sc)_all.deb

dpkg -i percona-release_0.1-4.$(lsb_release -sc)_all.deb

apt-get update

apt-get install percona-server-server-5.6

