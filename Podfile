platform :ios, '7.0'

inhibit_all_warnings!

pod 'AFNetworking', '~> 2.6.1'
pod 'SDWebImage', '~> 3.7.3'
pod 'Masonry', '~> 0.6.1'
pod 'UITableView+FDTemplateLayoutCell', '=1.3'
pod 'KVOController', '~> 1.0.3'
pod 'UIColor-Utilities', '1.0.1'

post_install do |installer|
    system './fix_header_search.sh'
    
end
