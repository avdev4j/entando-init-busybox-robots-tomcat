FROM busybox:1.36.0

COPY --chmod=0755 init.sh /init.sh

ENTRYPOINT [ "/init.sh" ]