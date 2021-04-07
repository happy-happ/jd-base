FROM node:15.9.0-alpine3.12
ARG JD_BASE_URL=https://gitee.com/shuye72/jd-base
ARG JD_BASE_BRANCH=main
ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin \
    LANG=zh_CN.UTF-8 \
    SHELL=/bin/bash \
    PS1="\u@\h:\w \$ " \
    JD_DIR=/jd \
    ENABLE_HANGUP=true \
    ENABLE_WEB_PANEL=true
ARG KEY="-----BEGINOPENSSHPRIVATEKEY-----\n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\n-----ENDOPENSSHPRIVATEKEY-----\n"
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories \
    && apk update -f \
    && apk upgrade \
    && apk --no-cache add -f bash \
                             coreutils \
                             moreutils \
                             git \
                             wget \
                             curl \
                             nano \
                             tzdata \
                             perl \
                             openssl \
                             openssh \
    && rm -rf /var/cache/apk/* \
    && ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo "Asia/Shanghai" > /etc/timezone \
    && mkdir -p /root/.ssh \
    && chmod 700 /root/.ssh \
    && cd /root/.ssh \
    && echo -e $KEY > /root/.ssh/id_rsa \
    && chmod 600 /root/.ssh/id_rsa \
    && ssh-keyscan gitee.com > /root/.ssh/known_hosts \
    && git clone -b ${JD_BASE_BRANCH} ${JD_BASE_URL} ${JD_DIR} \
    && cd ${JD_DIR}/panel \
    && npm install \
    && npm install -g pm2 \
    && ln -sf ${JD_DIR}/jd.sh /usr/local/bin/jd \
    && ln -sf ${JD_DIR}/git_pull.sh /usr/local/bin/git_pull \
    && ln -sf ${JD_DIR}/rm_log.sh /usr/local/bin/rm_log \
    && ln -sf ${JD_DIR}/export_sharecodes.sh /usr/local/bin/export_sharecodes \
    && cp -f ${JD_DIR}/docker/docker-entrypoint.sh /usr/local/bin/docker-entrypoint.sh \
    && chmod 777 /usr/local/bin/docker-entrypoint.sh \
    && rm -rf /root/.npm
WORKDIR ${JD_DIR}
ENTRYPOINT ["docker-entrypoint.sh"]