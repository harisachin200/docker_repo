FROM registry.gear.ge.com/dig-plm-platform/rhel7-base:latest

MAINTAINER Harikrishna Ande <harikrishna.ande@ge.com>
ENV http_proxy 'http://PITC-Zscaler-Americas-Alpharetta3PR.proxy.corporate.ge.com:80' && \
	https_proxy  ''

RUN yum install -y wget

#ADD http://archive.apache.org/dist/httpd/httpd-2.4.25.tar.gz /
#RUN wget --no-check-certificate -e use_proxy=yes -e http_proxy=http://PITC-Zscaler-Americas-Alpharetta3PR.proxy.corporate.ge.com:80 -e https_proxy=https://PITC-Zscaler-Americas-Alpharetta3PR.proxy.corporate.ge.com:443 $URL 	

