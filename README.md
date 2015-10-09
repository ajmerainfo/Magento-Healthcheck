# Magento-Healthcheck
ruby script to perform a health check of a magento system

Script is not yet ready for prime time and there are many things which are not yet being scanned.

Pull down and execute the script using

'''bash
wget https://github.com/cgarrigues/Magento-Healthcheck/raw/master/healthcheck
chmod +x wget
./healthcheck
'''

The output of the script include ANSI escape characters.  If you view the output through less, you will want to use the -R flag:

'''bash
./healthcheck | less -R
'''

|./healthcheck --verbose | include the full contents of all files checked |
|./healthcheck --quiet | minimize the output |

Updates and additions to the code in the form of Pull Requests are much appreciated.