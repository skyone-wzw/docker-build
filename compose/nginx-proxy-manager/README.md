<p align="center">
	<img src="https://nginxproxymanager.com/github.png">
	<br><br>
	<img src="https://img.shields.io/badge/version-2.9.16-green.svg?style=for-the-badge">
	<a href="https://hub.docker.com/repository/docker/jc21/nginx-proxy-manager">
		<img src="https://img.shields.io/docker/stars/jc21/nginx-proxy-manager.svg?style=for-the-badge">
	</a>
	<a href="https://hub.docker.com/repository/docker/jc21/nginx-proxy-manager">
		<img src="https://img.shields.io/docker/pulls/jc21/nginx-proxy-manager.svg?style=for-the-badge">
	</a>
	<a href="https://ci.nginxproxymanager.com/blue/organizations/jenkins/nginx-proxy-manager/branches/">
		<img src="https://img.shields.io/jenkins/build?jobUrl=https%3A%2F%2Fci.nginxproxymanager.com%2Fjob%2Fnginx-proxy-manager%2Fjob%2Fmaster&style=for-the-badge">
	</a>
	<a href="https://gitter.im/nginx-proxy-manager/community">
		<img alt="Gitter" src="https://img.shields.io/gitter/room/nginx-proxy-manager/community?style=for-the-badge">
	</a>
	<a href="https://reddit.com/r/nginxproxymanager">
		<img alt="Reddit" src="https://img.shields.io/reddit/subreddit-subscribers/nginxproxymanager?label=Reddit%20Community&style=for-the-badge">
	</a>
</p>

This project comes as a pre-built docker image that enables you to easily forward to your websites
running at home or otherwise, including free SSL, without having to know too much about Nginx or Letsencrypt.

该项目是一个 docker 镜像，使您能够轻松地反向代理任何地方运行的网站，包括免费的 SSL，而无需对 Nginx 或 Letsencrypt 有太多了解。

需要先开放 `81` 端口，配置对自身的反向代理，然后关闭 `81` 端口。
