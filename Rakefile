require 'xcodebuild'

task default: ['xcode:build']

XcodeBuild::Tasks::BuildTask.new do |t|
  t.target = 'macosvpn'
  t.configuration = "Release"
end