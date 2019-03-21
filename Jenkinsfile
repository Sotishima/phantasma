import com.mainstreethub.jenkins.pipelines.Notifier
import com.mainstreethub.jenkins.pipelines.node.library.Pipeline

def test() {
    // copy the settings.xml to the maven home dir
  echo "noop!"
}
new Pipeline(this).run([
  testStrategy: this.&test,
  notifier: new Notifier([steps: this, ownerChannels: ["gps-dify-rep-notify"]])
])
