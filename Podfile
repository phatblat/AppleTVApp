source 'https://github.com/CocoaPods/Specs.git'

platform :tvos, '9.1'
use_frameworks!
inhibit_all_warnings!

xcodeproj 'AppleTVApp'
# project 'AppleTVApp'
workspace 'AppleTVApp'

def testing_pods
    pod 'Quick', :git => 'git@github.com:phatblat/Quick.git', :branch => 'ben/tvos3'
    pod 'Nimble', :git => 'git@github.com:phatblat/Nimble.git', :branch => 'ben/tvos'
end

target 'AppleTVAppTests' do
    testing_pods
end
