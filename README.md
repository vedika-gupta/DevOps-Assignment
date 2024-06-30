<h1>DevOps Assignment - SRM University</h1>

<p><strong>Author:</strong> Vedika Gupta</p>

<h2>Assignment Overview</h2>
<p>The goal of this assignment is to create Kubernetes configurations to launch ClickHouse and Superset pods in Minikube and connect them.</p>

<h3>Prerequisites</h3>
<ul>
  <li>Kubernetes knowledge and Minikube installed locally</li>
  <li>Docker knowledge</li>
  <li>Understanding of ClickHouse and Superset</li>
</ul>

<h3>Steps Completed</h3>
<ol>
  <li><strong>ClickHouse Deployment</strong>:
    <ul>
      <li>Created a StatefulSet for ClickHouse with persistent storage of 10GB.</li>
      <li>Exposed the ClickHouse native port (9000) to connect with Superset.</li>
    </ul>
  </li>
  <li><strong>Superset Deployment</strong>:
    <ul>
      <li>Created a Deployment for Superset.</li>
      <li>Ensured Superset can be accessed via a web browser.</li>
    </ul>
  </li>
  <li><strong>Connecting ClickHouse to Superset</strong>:
    <ul>
      <li>Opened Superset in the browser.</li>
      <li>Added ClickHouse as a data source in Superset.</li>
    </ul>
  </li>
</ol>

<h3>Submission Details</h3>
<ul>
  <li>The YAML files (<code>clickhouse.yaml</code> and <code>superset.yaml</code>) are in the root directory.</li>
  <li>The code is uploaded to the GitHub repository.</li>
  <li>An email was sent with the subject “DevOps Assignment SRM University - Vedika Gupta” containing the GitHub URL.</li>
</ul>
