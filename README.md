# Prometheus-Grafana-Docker

[Prometheus, Grafana 와 Docker Compose를 이용한 모니터링 환경 구축](https://wonyong-jang.github.io/devops/2023/03/06/DevOps-Prometheus-Grafana-Docker-Compose.html)을 
참고하여 구성 했고, [Spring boot 어플리케이션](https://github.com/WonYong-Jang/Pharmacy-Recommendation)을 대상으로 모니터링 환경을 구축   

Grafana에서 제공하는 대시보드 [Spring boot statistics](https://grafana.com/grafana/dashboards/11378-justai-system-monitor/) 와 
[Resilience4j grafana](https://github.com/resilience4j/resilience4j/blob/master/grafana_dashboard.json) 를 import 하여 사용   

# Result

<img width="1500" alt="스크린샷 2023-03-08 오후 9 12 43" src="https://user-images.githubusercontent.com/26623547/223710602-5280ee69-bfec-4337-9cc9-d943c7b73382.png">

<img width="1500" alt="스크린샷 2023-03-08 오후 9 12 26" src="https://user-images.githubusercontent.com/26623547/223710625-d3dc0094-1817-47e0-b795-436334ec4cfa.png">


# Reference

<https://godekdls.github.io/Resilience4j/grafana/>  
<https://godekdls.github.io/Resilience4j/spring-boot-2-getting-started/>
<https://github.com/resilience4j/resilience4j/issues/1186>

