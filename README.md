# The following time format works with any of the
# Apache/NGINX's log formats below.
#
time-format %H:%M:%S
# The following date format works with any of the
# Apache/NGINX's log formats below.
#
date-format %d/%b/%Y
# NCSA Combined Log Format
log-format %h %^[%d:%t %^] "%r" %s %b "%R" "%u"
# NCSA Combined Log Format with Virtual Host
log-format %v:%^ %h %^[%d:%t %^] "%r" %s %b "%R" "%u"
