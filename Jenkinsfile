@Library('kube-pipeline-library') _
import com.example.*
node { checkout scm }
new Pipeline(this, "config.yml").execute()
