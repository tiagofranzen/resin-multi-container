FROM resin/%%RESIN_ARCH%%-alpine

RUN apk add --update ruby

WORKDIR /downloads
CMD /usr/bin/ruby -run -ehttpd . -p80
