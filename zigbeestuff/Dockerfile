ARG BUILD_FROM
FROM $BUILD_FROM

# Add env
ENV LANG C.UTF-8

# Copy data
COPY target/release/zigbeestuff /zigbeestuff
RUN chmod a+x /zigbeestuff

CMD [ "/zigbeestuff", "/config/zigbeestuff/config.tonl" ]
