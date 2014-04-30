require 'git-version-bump'

task :default => :test

desc "Run the testsuite"
task :test do
	sh "./test/run"
end

desc "Make a tarball release"
task :release do
	sh "git archive --format tar.gz "+
	    "--prefix 'dns323-firmware-tools-#{GVB.version}/' "+
	    "-o '../dns323-firmware-tools-#{GVB.version}.tar.gz' "+
	    "HEAD"

	sh "git push github"
end
