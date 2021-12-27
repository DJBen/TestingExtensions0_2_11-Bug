platform :ios, '15.0'
inhibit_all_warnings!

target 'TestingExtensions0_2_11-Bug' do
  use_modular_headers!
  
  pod "SwiftRex", "~> 0.8.8"
  pod "CombineRex", "~> 0.8.8"
  pod "CombineRextensions"

  target 'TestingExtensions0_2_11-BugTests' do
    inherit! :search_paths
    
    pod "TestingExtensions"
  end
end
