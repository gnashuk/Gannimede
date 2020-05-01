platform :ios, "11.0"

target 'Gannimede' do
    use_frameworks!
    pod 'Firebase/Storage', '~> 3.0.0'
    pod 'Firebase/Auth'
    pod 'Firebase/Database'
    pod 'FirebaseUI', '~> 5.0.0'
    pod 'Firebase/Messaging'
    pod 'JSQMessagesViewController'
    pod 'CryptoSwift'
    pod 'NYTPhotoViewer'
    pod 'BEMCheckBox'
    pod 'GoogleAPIClientForREST/Drive', '~> 1.2.1'
    pod 'GoogleSignIn', '~> 4.1.1'
    pod 'Alamofire', '~> 4.7'
    pod 'UIEmptyState', '~> 4.0.1'
end

post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
        config.build_settings.delete('CODE_SIGNING_ALLOWED')
        config.build_settings.delete('CODE_SIGNING_REQUIRED')
    end
end
