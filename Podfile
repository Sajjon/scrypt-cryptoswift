def import_pods
  pod 'CryptoSwift', '~> 0.10'
end

target 'ScryptmacOS' do
  platform :osx, '10.11'
#  use_frameworks!
  use_modular_headers!
  import_pods

  target 'ScryptmacOSTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

target 'ScryptiOS' do
  platform :ios, '11'
#  use_frameworks!
  use_modular_headers!
  import_pods

  target 'ScryptiOSTests' do
    inherit! :search_paths
    # Pods for testing
  end

end