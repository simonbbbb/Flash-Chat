platform :ios, '9.0'

target 'Flash Chat' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Flash Chat

pod 'Firebase'
pod 'Firebase/Auth'
pod 'Firebase/Database'
pod 'SVProgressHUD'
pod 'ChameleonFramework'
pod 'Firebase/Core'

end

post_install do |installer|
  installer.pods_project.build_configurations.each do |target|
    installer.pods_project.build_configurations.each do |config
      config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENT'] = 'NO'
      end
    end
  end
