# troubleshooting
The first time you execute `vagrant up` on this module, it will most probably fail, because `ext-2.2.zip` is no longer available for download on http://dev.sencha.com/deploy/ext-2.2.zip. You should be able to find it on the internet. Download it yourself and put it in the download_cache folder which is created the first time you run `vagrant up`. After that try `vagrant up` again and it should work.