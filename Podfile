
platform :ios, '6.0'
inhibit_all_warnings!

xcodeproj 'TiYandexMobileMetrica'

pod 'YandexMobileMetrica'

post_install do |installer|
  installer.project.targets.each do |target|
    puts "#{target.name}"
  end
end

