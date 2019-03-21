import com.mainstreethub.jenkins.pipelines.Notifier
import com.mainstreethub.jenkins.pipelines.node.library.Pipeline

new Pipeline(this).run([
  notifier: new Notifier([steps: this, ownerChannels: ["gps-dify-rep-notify"]])
])
