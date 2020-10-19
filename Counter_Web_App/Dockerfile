FROM ubuntu

MAINTAINER Marco Vazquez <marcorvazquezs@gmail.com>

COPY random_number.sh /usr/local/bin/random_number.sh

RUN chmox +x /usr/local/bin/random_number.sh

CMD ["/usr/local/bin/random_number.sh"]