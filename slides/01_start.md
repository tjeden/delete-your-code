!SLIDE center

<div class="folk_solid" style="font-size: 300px; margin-bottom: 40px">
delete 
</div>

!SLIDE center

<div class="folk_solid" style="font-size: 300px; margin-bottom: 40px">
your
</div>

!SLIDE center

<div class="folk_solid" style="font-size: 300px; margin-bottom: 40px">
code
</div>

!SLIDE center 

<div class="folk_shadow" style="font-size: 120px; margin: 50px">
1. Do not be afraid
</div>
<div class="folk_solid" style="font-size: 60px;">
&lt;of deleting the code&gt;
</div>

!SLIDE code smaller

    @@@ Ruby
    def some_very_long_method_you_are_ashamed
      conditions = {:conditions => ["activities.action = ? AND avatar_id is not null",'new_in_contest'],
        :joins => [:activities, :photos], :group => "users.id", :having => "COUNT(photos.id) > 5",
        :include => {:user_addresses => :city}, :order => "activities.created_at DESC",
        :per_page => 96, :page => params[:page] || 1}
      if params[:gender]
        conditions[:conditions][0] += " and users.gender = ?"
        conditions[:conditions] << params[:gender]
      end
      if params[:group] && !params[:group].eql?("0")
        conditions[:joins] << {:user_sexiest_contests => :sexiest_contest}
        conditions[:conditions][0] += " and sexiest_contests.age_group = ?"
        conditions[:conditions] << params[:group]
      end
      @users = User.paginate(conditions)
    end

!SLIDE code smaller

    @@@ Ruby
    def some_very_long_method_you_are_ashamed
      conditions = {:conditions => ["activities.action = ? AND avatar_id is not null",'new_in_contest'],
        :joins => [:activities, :photos], :group => "users.id", :having => "COUNT(photos.id) > 5",
        :include => {:user_addresses => :city}, :order => "activities.created_at DESC",
        :per_page => 96, :page => params[:page] || 1}
      # if params[:gender]
      #   conditions[:conditions][0] += " and users.gender = ?"
      #   conditions[:conditions] << params[:gender]
      # end
      # if params[:group] && !params[:group].eql?("0")
      #   conditions[:joins] << {:user_sexiest_contests => :sexiest_contest}
      #   conditions[:conditions][0] += " and sexiest_contests.age_group = ?"
      #   conditions[:conditions] << params[:group]
      # end
      @users = User.paginate(conditions)
    end

!SLIDE code smaller

    @@@ Ruby
    def some_very_long_method_you_are_ashamed
      conditions = {:conditions => ["activities.action = ? AND avatar_id is not null",'new_in_contest'],
        :joins => [:activities, :photos], :group => "users.id", :having => "COUNT(photos.id) > 5",
        :include => {:user_addresses => :city}, :order => "activities.created_at DESC",
        :per_page => 96, :page => params[:page] || 1}
      # if params[:gender]
      #   conditions[:conditions][0] += " and users.gender = ?"
      #   conditions[:conditions] << params[:gender]
      # end
      # if params[:group] && !params[:group].eql?("0")
      #   conditions[:joins] << {:user_sexiest_contests => :sexiest_contest}
      #   conditions[:conditions][0] += " and sexiest_contests.age_group = ?"
      #   conditions[:conditions] << params[:group]
      # end
      mystery_helper(conditions, params[:gender])
      @users = User.paginate(conditions)
    end

!SLIDE code smaller

    @@@ Ruby
    def some_very_long_method_you_are_ashamed
      conditions = {:conditions => ["activities.action = ? AND avatar_id is not null",'new_in_contest'],
        :joins => [:activities, :photos], :group => "users.id", :having => "COUNT(photos.id) > 5",
        :include => {:user_addresses => :city}, :order => "activities.created_at DESC",
        :per_page => 96, :page => params[:page] || 1}
      # We probably need to delete this
      # if params[:gender]
      #   conditions[:conditions][0] += " and users.gender = ?"
      #   conditions[:conditions] << params[:gender]
      # end
      # if params[:group] && !params[:group].eql?("0")
      #   conditions[:joins] << {:user_sexiest_contests => :sexiest_contest}
      #   conditions[:conditions][0] += " and sexiest_contests.age_group = ?"
      #   conditions[:conditions] << params[:group]
      # end
      mystery_helper(conditions, params[:gender])
      @users = User.paginate(conditions)
    end

!SLIDE center 

<div class="folk_shadow" style="font-size: 120px; margin: 50px">
2. Do not comment code
</div>

!SLIDE code
    @@@ Ruby
    # We probably need to delete this
    
!SLIDE code
    @@@ Ruby
    # We probably need to delete this 
    # Is it needed?

!SLIDE code
    @@@ Ruby
    # We probably need to delete this 
    # Is it needed?
    # TODO: check this out

!SLIDE code
    @@@ Ruby 
    # TODO: Fix this. Fix what?

!SLIDE code
    @@@ Ruby 
    # This is shitcrafting

!SLIDE code
    @@@ Ruby 
    # Here be dragons...

!SLIDE code
    @@@ Ruby 
    # This should be deleted after 10.09.2010

!SLIDE code
    @@@ Ruby 
    # if i ever see this again i'm going to 
    # start bringing guns to work

!SLIDE code
    @@@ Ruby 
    # drunk, fix later

!SLIDE code
    @@@ Ruby 
    # Magic. Do not touch.

!SLIDE center

<div class="folk_outline" style="font-size: 160px;">You do use GIT,</div>
<div class="folk_outline" style="font-size: 160px;">dont't you?</div>

!SLIDE center

<div class="folk_shadow" style="font-size: 120px;">so...</div>

!SLIDE title

## Delete your code  ##
!SLIDE code big
    

      > rm -rf /

!SLIDE center

<div class="folk_shadow" style="font-size: 120px;">no seriously</div>

!SLIDE title

# Delete #
# your #
# code#
