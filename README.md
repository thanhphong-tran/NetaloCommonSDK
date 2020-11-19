# Pods for NetaloCommonSDK
How to intergrate: 
#=================Init Podfile========================#
B1- Init Podfile
B2 -Add cmd in Podfile bellow:
#=================Add to Podfile=====================#

    pod 'NetaloCommonSDK', :git => 'http://gitlab.ecdc.vn/hieubui/NetaloCommonSDK'
    pod 'MessageKit', :git => 'http://gitlab.ecdc.vn/hieubui/nt-messagekit'
    pod 'Localize-Swift', :git => 'http://gitlab.ecdc.vn/hieubui/nt-Localize-Swift'
    pod 'Kingfisher', '~> 5.15'
    pod 'ReSwift', '~> 4.1.1'
    pod 'SwipeTransition', '~> 0.4.2'
    pod 'GoogleWebRTC', '~> 1.1'
    
    # Local database
    pod 'RealmSwift', '5.3.5'
    pod 'Reachability', '~> 3.2'
    pod 'ZIPFoundation', '~> 0.9'

    # Secret chat
    pod 'SignalCoreKit', git: 'https://github.com/signalapp/SignalCoreKit.git'
    pod 'AxolotlKit', git: 'https://github.com/signalapp/SignalProtocolKit.git', branch: 'master'
    pod 'HKDFKit', git: 'https://github.com/signalapp/HKDFKit.git'
    pod 'Curve25519Kit', git: 'https://github.com/signalapp/Curve25519Kit'
    pod 'GRKOpenSSLFramework', git: 'https://github.com/signalapp/GRKOpenSSLFramework', branch: 'mkirk/1.0.2t'
    
    pod 'Socket.IO-Client-Swift', '14.0.0'
#===================================================#
