<h1>☁️ CloudWave_FBU-Infra-Project</h1>

<!-- 대표 이미지 -->
![우숭사진](https://github.com/user-attachments/assets/81451b08-75c2-4b4e-be70-6848a6d3b605)
<br><br>

<h2>🎯 Project Overview</h2>
<ul>
  <li>대규모 트래픽 상황에서도 안정적으로 서비스를 운영할 수 있도록 인프라 자동화 및 확장성을 구현한 프로젝트</li>
  <li>AWS EKS 기반의 MSA 환경을 구축하고, GitLab CI/CD와 ArgoCD를 통한 GitOps 기반 배포 자동화를 적용</li>
  <li>모니터링, 보안, 백업까지 통합된 클라우드 네이티브 인프라 환경을 설계</li>
</ul>

<br>

<h2>📘 Notion Page</h2>
<h3><a href="https://sable-mars-102.notion.site/21fcb42f28df80149002f8b9a6f1b0f8?pvs=74" target="_blank">Project Documentation (Notion)</a></h3>
<br>

<h2>🧩 Tech Stack</h2>

<table>
  <tr>
    <th>Category</th>
    <th>Details</th>
  </tr>

  <tr>
    <td><strong>☁️ Cloud & Infra</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      AWS (EKS, EC2, S3, Route53, IAM, Backup)<br>
      Terraform • CloudFormation • Karpenter • KEDA • HPA<br><br>
      <strong>explanation:</strong><br>
      IaC 기반 인프라 관리, 오토스케일링, 고가용성 클러스터 구성
    </td>
  </tr>

  <tr>
    <td><strong>⚙️ DevOps & CI/CD</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      GitLab CI/CD • ArgoCD • GitOps Workflow<br>
      Docker • Kubernetes • Helm<br><br>
      <strong>explanation:</strong><br>
      GitLab → ArgoCD 자동화 파이프라인, Canary/Rolling 배포 전략 적용
    </td>
  </tr>

  <tr>
    <td><strong>🧠 Backend</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      Java • Spring Boot • JPA • Gradle<br><br>
      <strong>explanation:</strong><br>
      RESTful API 설계, MSA 구조 서비스 분리, 확장성 중심 백엔드 구성
    </td>
  </tr>

  <tr>
    <td><strong>💾 Database</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      Amazon Aurora (RDS) • ElastiCache (Redis)<br><br>
      <strong>explanation:</strong><br>
      Connection Pooling, Read Replica 구성, Cache Layer 최적화
    </td>
  </tr>

  <tr>
    <td><strong>💻 Frontend</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      Vue.js<br><br>
      <strong>explanation:</strong><br>
      관리용 UI 및 서비스 상태 시각화 페이지 구현
    </td>
  </tr>

  <tr>
    <td><strong>📡 Messaging & Scaling</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      Amazon SQS • Kafka<br><br>
      <strong>explanation:</strong><br>
      이벤트 기반 비동기 처리, 메시지 큐 기반 오토스케일링 환경 구축
    </td>
  </tr>

  <tr>
    <td><strong>📊 Monitoring & Observability</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      Prometheus • Grafana • Loki • Tempo • Kiali • Istio<br>
      OpenTelemetry (Metrics / Logs / Traces)<br><br>
      <strong>explanation:</strong><br>
      통합 모니터링 환경 구성, 메트릭·로그·트레이스 데이터 시각화
    </td>
  </tr>

  <tr>
    <td><strong>🔐 Security & Networking</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      VPC • PrivateLink • Security Groups • VPN<br>
      GuardDuty • WAF • ACM • KMS • IAM<br><br>
      <strong>explanation:</strong><br>
      네트워크 분리 및 접근 제어, TLS/HTTPS 암호화, IAM Role 기반 RBAC 적용
    </td>
  </tr>

  <tr>
    <td><strong>💬 Communication & Collaboration</strong></td>
    <td>
      <strong>Technologies:</strong><br>
      Notion • Slack • Jira<br><br>
      <strong>explanation:</strong><br>
      팀 협업, 일정 관리, 기술 문서 공유 및 스프린트 관리
    </td>
  </tr>
</table>
<br>
