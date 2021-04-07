FROM node:lts-alpine
ARG REPO=gitee
ARG REPO_URL=$REPO.com
ARG JD_SHELL=jd-base
ARG JD_SHELL_BRANCH=main
ARG JD_SHELL_HOST=jd_shell_gitee
ARG JD_SHELL_KEY="-----BEGINOPENSSHPRIVATEKEY-----\n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\n-----ENDOPENSSHPRIVATEKEY-----"
ARG JD_SCRIPTS=MyActions
ARG JD_SCRIPTS_BRANCH=main
ARG JD_SCRIPTS_HOST=jd_scripts_gitee
ARG JD_SCRIPTS_KEY="-----BEGINOPENSSHPRIVATEKEY-----\n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\n-----ENDOPENSSHPRIVATEKEY-----\n"
ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin \
	LANG=zh_CN.UTF-8 \
	SHELL=/bin/bash \
	PS1="\u@\h:\w $" \
	JD_DIR=/jd \
	ENABLE_TTYD=false \
	ENABLE_WEB_PANEL=false \
	ENABLE_HANGUP=false \
	ENABLE_RESET_REPO_URL=true \
	JD_SHELL_URL=git@jd_shell_gitee:shuye72/jd-base.git \
	JD_SCRIPTS_URL=git@jd_scripts_gitee:shuye72/MyActions.git 
WORKDIR /jd
RUN |10
REPO=gitee
REPO_URL=$REPO.com
JD_SHELL=jd-base
JD_SHELL_BRANCH=main
JD_SHELL_HOST=jd_shell_gitee
ARG JD_SHELL_KEY="-----BEGINOPENSSHPRIVATEKEY-----\n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\n-----ENDOPENSSHPRIVATEKEY-----"
JD_SCRIPTSMyActions
JD_SCRIPTS_BRANCH=main
JD_SCRIPTS_HOST=jd_scripts_gitee
ARG JD_SCRIPTS_KEY="-----BEGINOPENSSHPRIVATEKEY-----\n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\n-----ENDOPENSSHPRIVATEKEY-----\n"
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories \
	&& apk update -f \
	&& apk upgrade \
	&& apk --no-cache add -f bash \
							 coreutils \\
							 git \
							 wget \
							 curl \
							 nano \
							 tzdata \
							 perl \
							 openssh-client \
							 ttyd \
	&& rm -rf /var/cache/apk/* \
	&& ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
	&& echo "Asia/Shanghai" > /etc/timezone \
	&& mkdir -p /root/.ssh \
	&& echo -e $JD_SHELL_KEY > /root/.ssh/$JD_SHELL \
	&& echo -e $JD_SCRIPTS_KEY > /root/.ssh/$JD_SCRIPTS \
	&& chmod 600 /root/.ssh/$JD_SHELL /root/.ssh/$JD_SCRIPTS \
	&& echo -e "Host $JD_SHELL_HOST\n\tHostname $REPO_URL\n\tIdentityFile=/root/.ssh/$JD_SHELL\n\nHost $JD_SCRIPTS_HOST\n\tHostname $REPO_URL\n\tIdentityFile=/root/.ssh/$JD_SCRIPTS" > /root/.ssh/config \
	&& echo -e "\n\nHost *\n StrictHostKeyChecking no\n" >> /etc/ssh/ssh_config \
	&& chmod 644 /root/.ssh/config \
	&& ssh-keyscan $REPO_URL > /root/.ssh/known_hosts \
	&& git clone -b $JD_SHELL_BRANCH $JD_SHELL_URL $JD_DIR \
	&& cd $JD_DIR/panel \
	&& npm install \
	&& git clone -b $JD_SCRIPTS_BRANCH $JD_SCRIPTS_URL $JD_DIR/scripts \
	&& cd $JD_DIR/scripts \
	&& npm install \
	&& npm install -g pm2 \
	&& ln -sf $JD_DIR/jtask.sh /usr/local/bin/jd \
	&& ln -sf $JD_DIR/jtask.sh /usr/local/bin/jtask \
	&& ln -sf $JD_DIR/jtask.sh /usr/local/bin/otask \
	&& ln -sf $JD_DIR/jtask.sh /usr/local/bin/mtask \
	&& ln -sf $JD_DIR/jup.sh /usr/local/bin/git_pull \
	&& ln -sf $JD_DIR/jup.sh /usr/local/bin/jup \
	&& ln -sf $JD_DIR/jlog.sh /usr/local/bin/rm_log \
	&& ln -sf $JD_DIR/jlog.sh /usr/local/bin/jlog \
	&& ln -sf $JD_DIR/jcode.sh /usr/local/bin/export_sharecodes \
	&& ln -sf $JD_DIR/jcode.sh /usr/local/bin/jcode \
	&& ln -sf $JD_DIR/jcsv.sh /usr/local/bin/jcsv \
	&& cp -f $JD_DIR/docker/docker-entrypoint.sh /usr/local/bin/docker-entrypoint.sh \
	&& chmod 777 /usr/local/bin/docker-entrypoint.sh \
	&& chmod 777 $JD_DIR/*.sh \
	&& rm -rf /root/.npm # buildkit
ENTRYPOINT ["docker-entrypoint.sh"]